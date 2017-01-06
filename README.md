# Automationtraining


1. Create an GitHub repository https://help.github.com/articles/creating-a-new-repository/
2. All test files should be stored in the repository
3. Commit each coding session
4. Commit messages should represent changes


Test:

1. Visit https://www.skyscanner.net/
2. Click Login -> Register Here
3. Provide account name/password from Faker factory, install faker via command line by typing: pip install Faker

Faker usage example:

from faker import Faker
fake = Faker()

username = fake.user_name(*args, **kwargs)
# 'woodlynn'
password = fake.password(length=10, special_chars=True, digits=True, upper_case=True, lower_case=True)
# '7s!QH&Cg@I'

4. Assert "Check your inbox" text is present

