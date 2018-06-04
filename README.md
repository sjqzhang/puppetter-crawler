# puppeteer crawler




```
var crawler= async()=>{
  //var js=await loadjs('jquery.js,util.js');eval(js);
  //var $j=jQuery.noConflict();
  var js=await loadjs('util.js');eval(js);
  await $('#exec_btn').trigger('click')
 

 
  await sleep(500)


  return $('.table').text()

}

crawler()
```
 
