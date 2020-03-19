# Junitprog
package Unit.Testcases;

/**
 * Hello world!
 *
 */
public class App 
{
       public String remove(String s)
       {
    	   char f=s.charAt(0);
    	   char se=s.charAt(1);
    	   if(f=='A')
    		   if(se=='A')
    			   return s.substring(2,s.length());
    			   else
    				   return s.substring(1,s.length());
    	   else
    		    if(se=='A')
    			   return f+""+s.substring(2,s.length());
    	  
    	   return s;
       }
    
}
