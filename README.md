# Test-IronSoftware
## General Challenge

This project is a simulation of the old keypad from a Nokia legacy phone, implemented in C# with the following characteristics:

* Each button has a number to identify it, and pressing a button multiple times will cycle through the letters on it, allowing each button to represent more than one letter.  
  *Example: pressing `2` once will return `A`, but pressing it twice in succession will return `B`.*  
* You must pause for a second in order to type two characters from the same button one after another.  
  *Example: `222 2 22` → `CAB`.*

  1         2(ABC)     3(DEF)  

  4(GHI)    5(JKL)     6(MNO)  

  7(PQRS)   8(TUV)     9(WXYZ)  

   * (Bcksp) 0 (Space)  # (Send)  

## Examples of Output

("33#") =>  E

("227*#") =>  B

("4433555 555666#") =>  HELLO

## How It Will Be Implemented

- Using conditionals (`if` and `else`) and counters for each key.  
- Keeping the solution simple and easy to understand.  
- Adding comments in long conditional blocks.  
