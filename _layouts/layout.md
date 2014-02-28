<!DOCTYPE html>
<html class="fuelux" lang="en">
  <head>
    <meta http-equiv='Content-Type' content='text/html; charset=utf-8'>
    <title>{{ page.title }}</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="/js/all.js" type="text/javascript"></script>
    <link href="/css/bootstrap.min.css" rel="stylesheet">
    <link href="/css/custom.css" rel="stylesheet">

	
	
    <!-- Le HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->


<script type="text/javascript">
var _gaq = _gaq || [];
_gaq.push(['_setAccount', 'UA-48434878-1']);
_gaq.push(['_trackPageview']);
(function() {
var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;

ga.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'stats.g.doubleclick.net/dc.js';

var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
})();
</script>

  </head>
  <body>
    {% include navigation.md %}

    <div class="container">
        <div class="content">
            <div class="row">
		<div class="col-lg-2 col-md-1 hidden-sm hidden-xs">
		</div>
                <div class="col-lg-5 col-md-7 col-sm-8 col-xs-12">
                    {{ content }}
                </div>
                <div class="col-lg-3 col-md-3 col-sm-4 hidden-xs">
                    {% include aboutme.md %}
                </div>
		<div class="col-lg-2 col-md-1 hidden-sm hidden-xs">
		</div>
            </div>
        </div>
    </div>

    {% include footer.md %}
  </body>
</html>