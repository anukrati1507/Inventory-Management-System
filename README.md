### Inventory-Management-System


_Synopsis_

It is a spare parts inventory management system.


[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE) 
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=flat-square&logo=appveyor)](INSERT_UI_LINK_HERE)


## Screenshots

![Base Page](github_readme_resources/16849.jpg)


## Features
- [x]  Role based access control
- [x]  Admin Panel for granular access
- [x]  Sales and Purchase Departement as separate roles
- [x]  Jinja Templating with appropriate message identifiers


<br>

## Dependencies
 - Python
 - pip


## Running


To Get Started - Clone this repo
```bash
git clone https://github.com/anukrati1507/Inventory-Management-System
```

1. Creating a virtual environment

    ```bash
    virtualenv env
    ```
    In case you do not have virtualenv, you can install it using `pip install virtualenv`

2. Activating the virtualenv
   
   For Windows
   ```powershell
   .\env\Scripts\activate
   ```
   
   For Linux and Mac OS
   
   ```bash
   source env/bin/activate
   ```

3. Installing the dependencies
   
   ```bash
   pip install -r requirements.txt
   ```

4. To make migrations and migrate
   
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
5. To run the server
   
   ```bash
   python manage.py runserver
   ```

Upon starting the server goto [http:127.0.0.1:8000](http:127.0.0.1:8000) to get to the landing page.

## Contributors

<table>
	<tr align="center">
		<td>
		Anukrati Saxena
		<p align="center">
			<img src = "https://avatars.githubusercontent.com/u/47574465?v=4" width="150" height="150" alt="Anukarati Saxena">
		</p>
			<p align="center">
				<a href = "https://github.com/anukrati1507">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
				<a href = "https://www.linkedin.com/in/anukrati-saxena-7143001a0/">
					<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
				</a>
			</p>
		</td>
	</tr>
</table>

<p align="center">
	Made with ❤
</p>
