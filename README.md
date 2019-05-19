# PYTHON-RED-BLACK-TREES
A python implementation of red black trees.

Red black trees are a way of balacing binary search trees. The way it works is simple. On every insertion, it checks the state of the tree against a given set of rules, if it has violations it either does a color-flip or one of the 4 possible rotations and after one of these it does a color rearrangement also. There are 6 rules:


# RED BLACK TRREE RULES

 	1. Root is always black.
 	2. Every node is either red or black.
 	3. New node is always red.
 	4. No consecutive 2 red nodes.
 	5. Every path must have the same number of black nodes
 	6. Nulls are black

# Rebalance

      Black aunt --> rotate
      red aunt --> color-flip 
      
# After rotation 

        	BLACK
        	/   \
         RED    RED
        
# After color-flip

          RED
         /   \
      BLACK  BLACK

