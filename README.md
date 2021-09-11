# Flask-heroku-tools
Flask-heroku usefuls tools

# Welcome to Flask-heroku Deploying !
<ol>
<li>get to bash console</li>
<li><pre class=" language-term" style="position: relative;"><code class=" language-term">$ heroku login</code></pre></li>
<li>
<pre class=" language-term" style="position: relative;"><code class=" language-term"><span class="token input"><span class="token prompt">$ </span>cd myapp</span>
<span class="token input"><span class="token prompt">$ </span>git init</span>
Initialized empty Git repository in .git/
<span class="token input"><span class="token prompt">$ </span>git add .</span>
<span class="token input"><span class="token prompt">$ </span>git commit -m "My first commit"</span>
Created initial commit 5df2d09: My first commit
 44 files changed, 8393 insertions(+), 0 deletions(-)
 create mode 100644 README
 create mode 100644 Procfile
 create mode 100644 app/controllers/source_file
...
</code><div class="open_grepper_editor" title="Edit &amp; Save To Grepper"></div></pre>
</li>
<li> For a new Heroku app  <pre class=" language-term" style="position: relative;"><code class=" language-term"><span class="token input"><span class="token prompt">$ </span>heroku create</span>
Creating app... done, ⬢ thawing-inlet-61413
https://thawing-inlet-61413.herokuapp.com/ | https://git.heroku.com/thawing-inlet-61413.git
</code><div class="open_grepper_editor" title="Edit &amp; Save To Grepper"></div></pre></li>
<li><pre class=" language-term" style="position: relative;"><code class=" language-term"><span class="token input"><span class="token prompt">$ </span>git remote -v</span>
heroku  https://git.heroku.com/thawing-inlet-61413.git (fetch)
heroku  https://git.heroku.com/thawing-inlet-61413.git (push)
</code><div class="open_grepper_editor" title="Edit &amp; Save To Grepper"></div></pre></li>
<li>Deploying Code via heroku client<p>
 <code class=" language-term"><span class="token input"><span class="token prompt">$ </span>git push heroku master</span><br>
Initializing repository, done.
updating 'refs/heads/main'
...
</code></p></li>
<li>Done.</li>
</ol>

# To check Errors
To check errors use  the command  heroku logs --tail
# Refernces : 
https://devcenter.heroku.com/articles/git
