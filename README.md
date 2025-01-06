# linux project-1

**Creating a custom bash prompt**

1. "Prompt String 1" variable (PS1):
   
Defines the appearance of the primary shell prompt.

Highly customizable with escape sequences and special characters.

Enhances user experience and workflow efficiency.

**Customizations:** 
- Supports various placeholders
  - Username: \u
  - Hostname:
    
      Up to the first ".": \h
    
      The complete hostname: \H
  - Current working directory:

      \w (full path)
      W (last directory of the full path)
  - Time:

      in 24-hour format: \t
      in 12-hour format (with am / pm}: \@
  - Example:
    
      PS1="\ue\h: \w$ *

        

   
