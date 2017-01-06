# Automationtraining


1. Create an GitHub repository https://help.github.com/articles/creating-a-new-repository/
2. All test files should be stored in the repository
3. Commit each coding session
4. Commit messages should represent changes


Test:

1. Visit https://www.skyscanner.net/
2. Click Login -> Register Here
3. Provide email/password from Faker(https://faker.readthedocs.io/en/master/), install faker via command line by typing: pip install Faker
4. Assert "Check your inbox" text is present

Faker usage example:

```Python
from faker import Faker
fake = Faker()

email = fake.free_email()
# 'hillconor@gmail.com'
password = fake.password(length=10, special_chars=True, digits=True, upper_case=True, lower_case=True)
# '7s!QH&Cg@I'
```



