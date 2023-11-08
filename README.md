# javascript
speeds up page loading by a few seconds
# Unused JavaScript can slow down your page load speed :
- If the JavaScript is render-blocking, the browser must download, parse, compile, and evaluate the script before it can proceed with all of the other work that's needed for rendering the page.
- Even if the JavaScript is asynchronous (not render-blocking), the code competes for bandwidth with other resources while it's downloading, which has significant performance implications. Sending unused code over the network is also wasteful for mobile users who don't have unlimited data plans.

Reduce unused JavaScript and delay script loading until needed to lower bytes used by network activities
- *https://massa.net/_nuxt/8cc9329.js*
- *https://massa.net/_nuxt/fc77377.js*
- *https://massa.net/_nuxt/811156f.js*

These suggestions can help pages load faster. They do not directly affect Performance scores.
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
</head>
<body>
 
 <table>
 	<tr>
 		<td> URL </td>
 		<td> Transfer Size </td>
    <td> Potential Savings </td>
 	</tr>
 	<tr>
 		<td> https://massa.net/_nuxt/8cc9329.js </td>
 		<td> 131,9 KiB </td>
    <td> 69,7 KiB </td>
 	</tr>
   <tr>
 		<td> https://massa.net/_nuxt/fc77377.js </td>
 		<td> 111,7 KiB 2</td>
     <td> 45,4 KiB </td>
  </tr>
    <tr>
 		<td> https://massa.net/_nuxt/811156f.js </td>
 		<td> 87,6 KiB</td>
   <td> 36,1 KiB </td>

 </table>

</body>
</html>
