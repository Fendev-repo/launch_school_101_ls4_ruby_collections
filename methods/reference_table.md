Method | Action | Considers the return |Returns a new           |Length of returned 
       |        |  value of the block? |collection from method? | collection           
------------ | ------------- | --------------| --------------
each | Iteration |  No | No, it returns the original | Length of original
select | Selection | Yes, its truthiness | Yes | Length of original or less
map | Transformation | Yes | Yes | length of original