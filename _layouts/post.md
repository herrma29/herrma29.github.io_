---
layout: layout
---
				<p>
					{% if page.previous.url %} 
						<a href="{{page.previous.url}}" title="Previous Post: {{page.previous.title}}">
						&laquo; Previous Blog Post</a>  |
					{% endif %}
					  <a href="/archives/">Archives</a>  
					{% if page.next.url %}
						|  <a href="{{page.next.url}}" title="Next Post: {{page.next.title}}">Next Blog Post &raquo; 					</a>
					{% endif %}
				</p>    

<h1>{{ page.title }}</h1>
<h4>{{ page.date | date: "%B %e, %Y" }}</h4>
    
{% if page.video_url %}
 <div class="less-fancy-video-header">
  <iframe
   class="yt-embed"
   src="{{page.video_url }}?&rel=0&showinfo=0&autohide=1&hd=1&wmode=transparent"
   frameborder="0"
   allowfullscreen="true">
  </iframe>
 </div>
{% endif %}

{{ content }}


