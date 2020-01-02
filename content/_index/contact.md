+++
fragment = "contact"
#disabled = true
date = "2019-12-10"
weight = 1100
background = "light"
form_name = "defaultContact"

title = "Kontakt"
subtitle  = "Wir freuen uns über Ihre Nachricht!"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://tecta-immobilien.net" #default: formspree.io
email = "hilsberg@tecta-immobilien.net"
button = "Absenden" # defaults to theme default
button_text = "Absenden"
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Ihr Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Ihre Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Ihre Telefonnummer *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Ihre Nachricht *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
