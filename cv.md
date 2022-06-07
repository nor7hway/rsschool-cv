
# Alexey Karyagin
### Contact information
E-mail: karyagin.a.y@gmail.com
Telegram: @nor7hway 

### About me
I am currently doing backend development. I'm interested in frontend development.
### Skills

- Programming languages:
	- Python3, JS (learning), C++ (basic)
- Framework/Libraries:
	- Django, DRF, Graphene-Django, FastAPI (basic)
- DBMS:
	- PostgreSQL, SQLite, Redis, MongoDB (basic)
- ORM:
	- DjangoORM, SQLAlchemy (basic)
- Testing:
	- Pytest, unittest, Selenium, Appium
- VCS:
	- Git, Mercurial (basic)
- CI/CD:
	- Jenkins (basic)
- Docker, Docker-compose

### Code example 
<pre><code>
class Solution:
	def invertTree(self, root: Optional[TreeNode]) -> Optional[TreeNode]:
        if not root: return None
        root.left, root.right = self.invertTree(root.right), self.invertTree(root.left)
        return root
</code></pre>

### Languages
- Russian (Native)
- English (A2-B1)
