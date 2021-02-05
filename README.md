# HackerRank-Day-18-Queues-and-Stacks
  

     public class Solution {
    
    LinkedList<Character> queue = new LinkedList<Character>();
    Stack<Character> stack = new Stack<Character>();
    
    void pushCharacter(char ch){  // inserting values to stack
            stack.push(ch);
                       
     }
      void enqueueCharacter(char ch){   //inserting values to queue
          queue.add(ch);
          
      }
      
      char popCharacter() {    // removing  values from stack
          return stack.pop();
           
      }
      char dequeueCharacter(){  //removing  values from queue
           return queue.remove();
           
      } 
    
    
