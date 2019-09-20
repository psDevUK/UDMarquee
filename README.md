# UDMarquee

Add some bling to your [Universal Dashboard](https://ironmansoftware.com/powershell-universal-dashboard).

This function has 2 parameters -Text which is a string anything typed in the text parameter enclosed in speechmarks will be output to the screen.  The second parameter is fontSize which expects an integer value.  Specifying a parameter for fonSize will increas/decrease the size of your text.  The default fontSize if not specified is 50. 
 
 Example:-
 New-UDMarquee -Text "Universal Dashboard is AWESOME" -fontSize 40
