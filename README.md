# student_management_system_in_django
student_management_system_in_django

<h2>Installation Steps : </h2>

<p>Project Dependency :</p>
<pre>
pip install -r requirements.txt
pip install requests
pip install Django
pip install mysql-client
</pre>
<hr>
<ul>
<ol>Change Database Setting in settings.py </ol>
<ol>
Run Migration Command 
<pre>
python manage.py makemigrations
python manage.py migrate
</pre>
 <ul>     
<li>In login_page.html Replace <pre>CAPTCHA_CLIENT_KEY</pre> with Captcha Client Side Key</li>
<li>In views.py Replace <pre>CAPTCHA_SERVER_KEY</pre> with Captcha SERVER Side Key</li>
<li>For website Visit <a href="https://akashshankar.pythonanywhere.com/">https://akashshankar.pythonanywhere.com/</a></li>
</ul>
</ol>
<ol>
Run Project python runserver
</ol>
</ul>
<hr>
<hr>

<h2>Database Design</h2>

<img src="https://github.com/hackstarsj/student_management_system_part_11/blob/master/screenshots/database.png" alt="Database Design">

