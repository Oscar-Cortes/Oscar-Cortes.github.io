# My Projects
Here is a list of Projects that I am working on:
# My Interests
I'm interested in teaching novice coders about computer science!
# My Blog
I'm really excited to blog my journey on GitHub.com.

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

<ul>
<li><a href="https://sarah-wecan.github.io/HelloWorld/">Hello
World Project</a></li>
<li><a href="https://github.com/thewecanzone/GitHubForDummies
Readers">GitHub For Dummies Repo</a></li>
</ul>

<ul>
<li><a href="https://twitter.com/{{ site.twitter_username}}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username}}">GitHub</a></li>
</ul>
