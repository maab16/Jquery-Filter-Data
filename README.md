# Jquery-Filter-Data
Filter Data with Jquery animation

# Installation
insert this two files just before end body tag
```
<script src="js/jquery.min.js"></script>
<script src="js/filter.min.js"></script>
```

then call filter plugin
```
<script type="text/javascript">
	$(document).ready(function(){
		$('.portfolios').filterData({
			aspectRatio: '8:5', // how many height for single item
		});
	});
</script>
```
