# HackerRank-Day-18-Queues-and-Stacks



public class Solution {
    // Write your code here.
    LinkedList<Character> queue = new LinkedList<Character>();  
    Stack<Character> stack = new Stack<Character>();  // specify the stack type with character
    

     void pushCharacter(char ch){ 
            stack.push(ch);
                       
     }
      void enqueueCharacter(char ch){
          queue.add(ch);
          
      }
      
      char popCharacter() { 
          char temp;
          temp = stack.pop();
          return temp;
      }
      char dequeueCharacter(){
           char temp;
          temp = queue.remove();
          return temp;
      } 
    
    
