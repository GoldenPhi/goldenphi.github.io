---
layout: page
title: Resources
tagline: Collection of libraries for web development
group: navigation
---
{% include JB/setup %}

To include any of these libraries, just copy-paste the HTML tags inside your `<head></head>` tags

```html
<!-- jQuery -->
<script src="http://goldenphi.github.io/resources/jquery-1.11.1.min.js"></script>
<script src="http://goldenphi.github.io/resources/jquery-2.1.1.min.js"></script>

<!-- Bootstrap -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/bootstrap/css/bootstrap.min.css">
<link rel="stylesheet" href="http://goldenphi.github.io/resources/bootstrap/css/bootstrap-theme.min.css">
<script src="http://goldenphi.github.io/resources/bootstrap/js/bootstrap.min.js"></script>

<!-- FontAwesome -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/font-awesome/css/font-awesome.min.css">

<!-- Animate.css -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/animate.css">

<!-- WOW.js -->
<script src="http://goldenphi.github.io/resources/wow.min.js"></script>
<script>
	new WOW().init();
</script>

<!-- moment.js -->
<script src="http://goldenphi.github.io/resources/moment.js"></script>
<script>
	moment().format();
</script>

<!-- midnight.js -->
<script src="http://goldenphi.github.io/resources/midnight.jquery.min.js"></script>
<script>
	// Start midnight
	$(document).ready(function() {
		// Change this to the correct selector
		$('nav.fixed').midnight();
	});
</script>

<!-- D3.js -->
<script src="http://goldenphi.github.io/resources/d3.min.js" charset="utf-8"></script>

<!-- require.js -->
<!-- Fill data-main="" -->
<script data-main="" src="http://goldenphi.github.io/resources/require/require.min.js"></script>

<!-- pure css -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/pure/pure-min.css">

<!-- chart.js -->
<script src="http://goldenphi.github.io/resources/chart/Chart.min.js"></script>

<!-- Snap.svg -->
<script src="http://goldenphi.github.io/resources/snap.svg/snap.svg-min.js"></script>

<!-- Leaflet -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/leaflet/leaflet.css" />
<script src="http://goldenphi.github.io/resources/leaflet/leaflet.min.js"></script>

<!-- Vue.js -->
<script src="http://goldenphi.github.io/resources/vue.min.js"></script>

<!-- Seedrandom -->
<script src="http://goldenphi.github.io/resources/seedrandom.min.js"></script>

<!-- Underscore.js -->
<script src="http://goldenphi.github.io/resources/underscore-min.js"></script>
```