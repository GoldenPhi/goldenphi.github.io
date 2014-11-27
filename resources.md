---
layout: page
title: Resources
tagline: Collection of libraries for web development
group: navigation
---
{% include JB/setup %}

### Links

- [jQuery](http://jquery.com)
- [Bootstrap](http://getbootstrap.com)
- [FontAwesome](http://fortawesome.github.io/Font-Awesome)
- [Animate.css](http://daneden.github.io/animate.css)
- [WOW.js](http://mynameismatthieu.com/WOW/index.html)
- [highlight.js](https://highlightjs.org)
- [Ladda](http://lab.hakim.se/ladda/)
- [Fokus](http://lab.hakim.se/fokus/)
- [Meny](http://lab.hakim.se/meny/)
- [forkit.js](http://lab.hakim.se/forkit-js/)
- [Stroll](http://lab.hakim.se/scroll-effects/)
- [Moment.js](http://momentjs.com)
- [Midnight.js](http://aerolab.github.io/midnight.js)
- [D3.js](http://d3js.org)
- [Require.js](http://requirejs.org)
- [PureCSS](http://purecss.io)
- [Chart.js](http://www.chartjs.org)
- [Snap.svg](http://snapsvg.io)
- [Leaflet](http://leafletjs.com)
- [Vue.js](http://vuejs.org)
- [Seedrandom](https://github.com/davidbau/seedrandom)
- [Underscore.js](http://underscorejs.org)

---

To include any of these libraries, just copy-paste the HTML tags inside your `<head></head>` tags

{% highlight html %}
<!-- jQuery -->
<!-- Use only one version -->
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

<!-- highlight.js -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/highlight/styles/monokai_sublime.css">
<script src="http://goldenphi.github.io/resources/highlight/highlight.pack.js"></script>
<script>hljs.initHighlightingOnLoad();</script>

<!-- Ladda -->
<!-- Use only one stylesheet and one ladda script -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/ladda/ladda.min.css">
<link rel="stylesheet" href="http://goldenphi.github.io/resources/ladda/ladda-themeless.min.css">
<script src="http://goldenphi.github.io/resources/ladda/ladda.min.js"></script>
<script src="http://goldenphi.github.io/resources/ladda/ladda.jquery.min.js"></script>
<script src="http://goldenphi.github.io/resources/ladda/spin.min.js"></script>

<!-- Fokus -->
<script src="http://goldenphi.github.io/resources/fokus.min.js"></script>

<!-- Meny -->
<!-- The stylesheet is optional -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/meny/meny-theme.css">
<script src="http://goldenphi.github.io/resources/meny/meny.js"></script>

<!-- forkit.js -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/forkit.js/forkit.css">
<script src="http://goldenphi.github.io/resources/forkit.js/forkit.js"></script>

<!-- Stroll -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/stroll/stroll.min.css">
<script src="http://goldenphi.github.io/resources/stroll/stroll.min.js"></script>

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
<script data-main="" src="http://goldenphi.github.io/resources/require.min.js"></script>

<!-- pure css -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/pure-min.css">

<!-- chart.js -->
<script src="http://goldenphi.github.io/resources/Chart.min.js"></script>

<!-- Snap.svg -->
<script src="http://goldenphi.github.io/resources/snap.svg-min.js"></script>

<!-- Leaflet -->
<link rel="stylesheet" href="http://goldenphi.github.io/resources/leaflet/leaflet.css" />
<script src="http://goldenphi.github.io/resources/leaflet/leaflet.min.js"></script>

<!-- Vue.js -->
<script src="http://goldenphi.github.io/resources/vue.min.js"></script>

<!-- Seedrandom -->
<script src="http://goldenphi.github.io/resources/seedrandom.min.js"></script>

<!-- Underscore.js -->
<script src="http://goldenphi.github.io/resources/underscore-min.js"></script>
{% endhighlight %}

---
