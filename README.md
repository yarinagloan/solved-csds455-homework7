Download Link: https://assignmentchef.com/product/solved-csds455-homework7
<br>
<strong>Problem 1</strong>: Prove that the graph obtained from <em>K<sub>n </sub></em>by deleting one edge has (<em>n </em>− 2)<em>n<sup>n</sup></em><sup>−3 </sup>spanning trees.

<strong>Problem 2</strong>: Let <em>G </em>be a connected graph in which each edge has a positive weight/length. Recall that Dijkstra’s algorithm takes a vertex <em>s </em>of <em>G </em>and creates a <em>shortest path spanning tree T </em>from <em>s</em>. If <em>T </em>is a shortest path spanning tree from <em>s</em>, then <em>d<sub>T</sub></em>(<em>s,v</em>) = <em>d<sub>G</sub></em>(<em>s,v</em>) for all <em>v </em>∈ <em>V </em>(<em>G</em>).

We can also create a shortest path spanning tree from a <em>point </em>on an edge. Consider edge <em>uv </em>of <em>G </em>and any point <em>χ </em>on <em>uv</em>. Let <em>T<sub>χ </sub></em>be a shortest path spanning tree from <em>χ </em>such that <em>d<sub>T</sub></em><em><sub>χ</sub></em>(<em>χ,v</em>) = <em>d<sub>G</sub></em>(<em>χ,v</em>) for all <em>v </em>∈ <em>V </em>(<em>G</em>).

There are an infinite number of points along any single edge, and we can create a shortest path spanning tree from each of these points. However, there are only a finite number of possible spanning trees of <em>G </em>(at most <em>n<sup>n</sup></em><sup>−2 </sup>from Monday’s class); therefore, there will be many points <em>χ </em>and <em>χ</em><sup>0 </sup>for which the shortest path spanning trees <em>T<sub>χ </sub></em>and <em>T<sub>χ</sub></em>0 are identical.

Furthermore, let’s say two spanning trees <em>T</em><sub>1 </sub>and <em>T</em><sub>2 </sub>are <em>equivalent </em>if for all <em>x </em>∈ <em>V </em>, <em>d<sub>T</sub></em><sub>1</sub>(<em>u,x</em>) = <em>d<sub>T</sub></em><sub>2</sub>(<em>u,x</em>) and <em>d<sub>T</sub></em><sub>1</sub>(<em>v,x</em>) = <em>d<sub>T</sub></em><sub>2</sub>(<em>v,x</em>). Let <em>S </em>be a set of spanning trees. Let’s define a <em>class </em>of equivalent trees to be a maximum subset of <em>S </em>such that all trees in the subset are equivalent to each other.

Let <em>S<sub>uv </sub></em>be the set of all shortest path spanning trees that are rooted at a point along the edge <em>uv</em>. How many separate classes of equivalent spanning trees can there be in <em>S<sub>uv</sub></em>? Prove your answer.