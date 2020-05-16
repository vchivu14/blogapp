#blogapp


<ol>
  <li>git clone https://github.com/vchivu14/blogapp.git</li>
  <li>cd blogapp</li>
  <li>python3 -m venv venv</li>
  <li>source venv/bin/activate</li>
  <li>pip install -r requirements.txt</li>
  <li>python3 manage.py migrate</li>
  <li>python3 manage.py createsuperuser</li>
  <li>python3 manage.py runserver</li>
  <li>check localhost:8000</li>
</ol>
<h5> Create a file named config.json on your computer with credentials to enable mail retrieval</h5>
<p>
$ sudo nano /etc/config.json
</p>
<p>
# and paste in your own credentials
</p>
<p>
{
        "EMAIL_USER": "",
        "EMAIL_PASS": ""
}
</p>
