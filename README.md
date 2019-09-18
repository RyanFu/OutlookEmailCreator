## Outlook Account Creator
Built with:
- Selenium
- Requests
- Faker
- CaptchaSolver

Creates new email account on outlook.com

### How to use

#### Basic
```python
# Initialize account creator
account_creator = OutlookAccountCreator()
# Run account creator
account_creator.create_account()
# Account created
```
#### With proxies
```python
# Load proxies from file
Proxies.load_proxies('path/to/proxies.txt')
# Initialize account creator
account_creator = OutlookAccountCreator(use_proxy=True)
# Run account creator
account_creator.create_account()
# Account created
```
