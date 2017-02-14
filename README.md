[![Build Status](https://travis-ci.org/pages-themes/modernist.svg?branch=master)](https://travis-ci.org/pages-themes/modernist) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-modernist.svg)](https://badge.fury.io/rb/jekyll-theme-modernist)

*Modernist is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/modernist), or even [use it today](#usage).*

![Thumbnail of modernist](thumbnail.png)

# Jquery-Filter-Data
Filter Data with Jquery animation

# Installation
insert this two files just before end body tag

<script src="js/jquery.min.js"></script>
<script src="js/filter.min.js"></script>

then call filter plugin

<script type="text/javascript">
	$(document).ready(function(){
		$('.portfolios').filterData({
			aspectRatio: '8:5', // how many height for single item
		});
	});
</script>
