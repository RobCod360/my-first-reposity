# This is my reposity
## My name is CAT
![this is img]![image](https://github.com/RobCod360/my-first-reposity/assets/150602176/a1521e9b-dae2-422f-b783-0bf0704c93b8)
######i'm **javascript developer.** *There is Example of my code:*
```javascript
let params = $("#filters").serialize()
	console.log(params)
	$.ajax(`http://www.boredapi.com/api/activity/?${params}`,{
		success:function(result){
			$("#result").show();
			let html = `
			<p>Activity: ${result.activity}</p>
			<p>Price: ${result.price}$</p>
			<p>Type: ${result.type}</p>`
			$("#result").html(html);
			$("#randAc").html("Randomize Again")
		},
		error:function(xhr){
			console.log(xhr.statusText);
		}
	})
});
```
This is unordered list:
* [my facebook](http://github.com)
* [my website](http://github.com)
* [my telegram](http://github.com)
