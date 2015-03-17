This is my midterm.

****NOTE:

      In Step #4: Resolving "http://t.co" into "1.usa.gov" sometimes twitter-text-python does not work. 
      This is a problem with the API not the actual code.
      
      In order to continue you must get step #4 to work. If it throws an exception what I have done is the following:
      1: Restart the kernel.
      2: I replace the following line 'result = p.parse("http://t.co/Dv6Jqbwu8H")' . I take out the url and replace the 
         parameter string with something else. For example like this 'result = p.parse("@medinaruizk")' . I run the code 
         block once, then I change the line back to the original and it works. I am unaware of why this happens with the 
         twitter-text-python module. 
         
      Step #4 is important because if twitter-text-=ython api calls are not working then you can't run the actual twitter
      query code block.
      
      Once again this is a problem with the twitter-text-python API. If you know the reason for this inconsistency please
      let me know.
