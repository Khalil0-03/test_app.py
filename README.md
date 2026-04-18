# test_app.py
from app import add

def test_add():
    assert add(2, 3) == 5
    def test_add():
    assert add(2, 3) == 6   # WRONG on purpose
    git add .
git commit -m "Break test"
git push
def test_add():
    assert add(2, 3) == 5
    git add .
git commit -m "Fix test"
git push
