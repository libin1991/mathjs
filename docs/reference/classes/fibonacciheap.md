---
layout: default
---

<a name="FibonacciHeap"></a>
<h2 id="fibonacciheap">FibonacciHeap <a href="#fibonacciheap" title="Permalink">#</a></h2>
* [new FibonacciHeap()](#new_FibonacciHeap_new)
* _instance_
	* [.insert()](#FibonacciHeap+insert)
	* [.size()](#FibonacciHeap+size)
	* [.clear()](#FibonacciHeap+clear)
	* [.isEmpty()](#FibonacciHeap+isEmpty)
	* [.extractMinimum()](#FibonacciHeap+extractMinimum)
	* [.remove()](#FibonacciHeap+remove)
* _static_
	* [._decreaseKey()](#FibonacciHeap._decreaseKey)
	* [._cut()](#FibonacciHeap._cut)
	* [._cascadingCut()](#FibonacciHeap._cascadingCut)
	* [._linkNodes()](#FibonacciHeap._linkNodes)

<a name="new_FibonacciHeap_new"></a>
<h3 id="new-fibonacciheap">new FibonacciHeap() <a href="#new-fibonacciheap" title="Permalink">#</a></h3>
Creates a new instance of a Fibonacci Heap.

<a name="FibonacciHeap+insert"></a>
<h3 id="fibonacciheapinsert">fibonacciHeap.insert() <a href="#fibonacciheapinsert" title="Permalink">#</a></h3>
Inserts a new data element into the heap. No heap consolidation is

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap+size"></a>
<h3 id="fibonacciheapsize">fibonacciHeap.size() <a href="#fibonacciheapsize" title="Permalink">#</a></h3>
Returns the number of nodes in heap. Running time: O(1) actual.

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap+clear"></a>
<h3 id="fibonacciheapclear">fibonacciHeap.clear() <a href="#fibonacciheapclear" title="Permalink">#</a></h3>
Removes all elements from this heap.

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap+isEmpty"></a>
<h3 id="fibonacciheapisempty">fibonacciHeap.isEmpty() <a href="#fibonacciheapisempty" title="Permalink">#</a></h3>
Returns true if the heap is empty, otherwise false.

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap+extractMinimum"></a>
<h3 id="fibonacciheapextractminimum">fibonacciHeap.extractMinimum() <a href="#fibonacciheapextractminimum" title="Permalink">#</a></h3>
Extracts the node with minimum key from heap. Amortized running 

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap+remove"></a>
<h3 id="fibonacciheapremove">fibonacciHeap.remove() <a href="#fibonacciheapremove" title="Permalink">#</a></h3>
Removes a node from the heap given the reference to the node. The trees

**Kind**: instance method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap._decreaseKey"></a>
<h3 id="fibonacciheap_decreasekey">FibonacciHeap._decreaseKey() <a href="#fibonacciheap_decreasekey" title="Permalink">#</a></h3>
Decreases the key value for a heap node, given the new value to take on.

**Kind**: static method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap._cut"></a>
<h3 id="fibonacciheap_cut">FibonacciHeap._cut() <a href="#fibonacciheap_cut" title="Permalink">#</a></h3>
The reverse of the link operation: removes node from the child list of parent.

**Kind**: static method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap._cascadingCut"></a>
<h3 id="fibonacciheap_cascadingcut">FibonacciHeap._cascadingCut() <a href="#fibonacciheap_cascadingcut" title="Permalink">#</a></h3>
Performs a cascading cut operation. This cuts node from its parent and then

**Kind**: static method of <code>[FibonacciHeap](#FibonacciHeap)</code>  
<a name="FibonacciHeap._linkNodes"></a>
<h3 id="fibonacciheap_linknodes">FibonacciHeap._linkNodes() <a href="#fibonacciheap_linknodes" title="Permalink">#</a></h3>
Make the first node a child of the second one. Running time: O(1) actual.

**Kind**: static method of <code>[FibonacciHeap](#FibonacciHeap)</code>  