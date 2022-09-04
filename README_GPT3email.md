## Usage of Daisi

It is recommended to use this application on the daisi platform itself using the link https://app.daisi.io/daisies/vijay/GPT-3%20Email%20Generator/app. However, you can still use your own editor using the below method:

### First, load the Packages:

```
import pydaisi as pyd
gpt_3_email_generator = pyd.Daisi("vijay/GPT-3 Email Generator")
```

### Now, connect to Daisi and access the functions using:
### Generate email

```
gpt_3_email_generator.generate_email(key, userPrompt="Write me a professionally sounding email", start="Dear").value
```
Returns a generated an email using GPT3 with a certain prompt and starting sentence