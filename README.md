# Jquery-Filter-Data
Filter Data with Jquery animation

# Installation
put html code
```html
<div class="container">
	<h2 class="work-title title text-center">My Awesome <strong>Work</strong></h2>
	<div class="row portfolio-controllers-container">
		<div class="portfolio-controllers wow fadeLeft" data-wow-duration="1s" data-wow-delay=".1s">
			<button type="button" class="filter-btn active-work" data-filter="all">All</button>
			<button type="button" class="filter-btn" data-filter=".web-design">Web Design</button>
			<button type="button" class="filter-btn" data-filter=".web-development">Web Development</button>
			<button type="button" class="filter-btn" data-filter=".graphics">Graphics</button>
			<button type="button" class="filter-btn" data-filter=".wordpress">Wordpress</button>
		</div>
	</div>
</div>
<div class="portfolios">
	<div class="col-md-4 col-sm-6 portfolio web-design">
		<figure class="portfolio-image">
			<img src="https://image-store.slidesharecdn.com/eb72935e-e9f6-4670-a914-8bc45f334d46-large.jpeg" alt="" class="img-responsive">
		</figure>
	</div>
	<div class="col-md-4 col-sm-6 portfolio wordpress web-development">
		<figure class="portfolio-image">
			<img src="https://dev.opera.com/articles/extension-developer-interviews-wot/team.jpg" alt="" class="img-responsive">
		</figure>
	</div>
	<div class="col-md-4 col-sm-6 portfolio web-design">
		<figure class="portfolio-image">
			<img src="http://developer.parrot.com/img/carousel2.jpg" alt="" class="img-responsive">
		</figure>
	</div>
	<div class="col-md-4 col-sm-6 portfolio wordpress web-design">
		<figure class="portfolio-image">
			<img src="http://blog.edx.org/wp-content/uploads/2017/01/android-featured.jpg" alt="" class="img-responsive">
		</figure>
	</div>
	<div class="col-md-4 col-sm-6 portfolio web-development">
		<figure class="portfolio-image">
			<img src="https://i.ytimg.com/vi/5YQkWQbDS9w/maxresdefault.jpg" alt="" class="img-responsive">
		</figure>
	</div>
			
<div class="more more-work more-container text-center">
	<a href="#">See More</a>
</div>
```
insert this two files just before end body tag
```html
<script src="js/jquery.min.js"></script>
<script src="js/filter.min.js"></script>
```

then call filter plugin
```javascript
<script type="text/javascript">
	$(document).ready(function(){
		$('.portfolios').filterData({
			aspectRatio: '8:5', // how many height for single item
		});
	});
</script>
```
