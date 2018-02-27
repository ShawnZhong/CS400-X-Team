 # X-Team 75 Style Guide

Basically follow the default Eclipse style: ctrl + alt + F

## Naming conventions
Somewhat descriptive name

### Examples
   * interfaces
       * UpperCamelCase.
       * The name is typically noun or noun phrase (e.g. ListADT) sometimes adjective (e.g. Comparable).
   * classes
       * UpperCamelCase.
       * The name is most noun or noun phrase (e.g. BalancedSearchTree). 
   * exception
       * UpperCamelCase.
       * Example: use 'DuplicateKeyException' instead of 'duplicateKeyException' or 'duplicate_key_exception'
   * fields
       * lowerCamelCase.
       * Example: use 'itemCount' instead of 'item_count' or 'ItemCount'
   * methods
       * lowerCamelCase.
       * Example: use 'updateNode' instead of 'UpdateNode' or 'update_node'
   * parameters
       * lowerCamelCase.
       * Example: use 'leftChild' instead of 'LeftChild' or 'left_child'
   * local variables: lowerCamelCase.
   * instance constants
       * CONSTANT_CASE: all uppercase letters, with words separated by underscores. 
       * Example: Use 'INITIAL_SIZE' instead of 'initialSize' or "initial_size"
   * class constants
       * CONSTANT_CASE: all uppercase letters, with words separated by underscores. 


## Commenting style for public and private members of a class or interface:

Try not to use inline comment (i.e. use a seperate line for commenting before the code that your want to comment on)@param
Include @author, @param, @return, @throws if possible

### Examples

* classes
* fields
* constructors
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
