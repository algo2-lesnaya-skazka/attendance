Git cheat sheet

Check personal configuration
<pre><code>$ git config --global -l</code></pre>

if needed change name and email
<pre><code>$ git config --global user.name "John Doe" 
$ git config --global user.email johndoe@example.com
$ git config --global -l</code></pre>

<pre><code>$ git clone https://github.com/algo2-lesnaya-skazka/attendance
$ cd attendance/
$ git branch -av
$ git checkout -b your_branch</code></pre>

Add yor name and email to attendance<current date>.md accordint to a pattern in it

<pre><code>$ git commit -am  “Add your_name yor_surname”
$ git push origin your_branch</code></pre>
