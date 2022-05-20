# django_email_to_gmai :envelope:

## Sending email :outbox_tray:
Although Python provides a mail sending interface via the smtplib module, Django provides a couple of light wrappers over it. These wrappers are provided to make sending email extra quick, to help test email sending during development, and to provide support for platforms that can’t use SMTP.



## Quick example :truck:

            from django.core.mail import send_mail

            send_mail(
                'Subject here',
                'Here is the message.',
                'from@example.com',
                ['to@example.com'],
                fail_silently=False,
            )
            
## Setting.py
            
            DEFAULT_AUTO_FIELD = 'django.db.models.BigAutoField'
            # Email Configuration
            EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
            EMAIL_HOST = 'smtp.gmail.com'
            EMAIL_PORT = '587'
            EMAIL_HOST_USER = 'here is email'
            EMAIL_HOST_PASSWORD = 'here email password'
            EMAIL_USE_TLS = True

# Very Commpn Error :interrobang:

## Fix error code 10060 connection timeout in django email sending process... 

<b>
if 10060 response time is make your headache then, it's mean that you have not set mail outlook on your pc. so pelase go through this link and it will help to fix this 10060 soket error. :clapper: </b>
<br>

https://www.youtube.com/watch?v=THkAdFNy164
            
            https://www.youtube.com/watch?v=THkAdFNy164

#### This can fix through : Verify web proxy connection.

### Follow the following steps: 
step 1:

    ipconfig/release

step 2:

    ipconfig /renew

step 3:

    ipconfig /flushdns
  
step 4:

    netsh winsock reset


##### YouTube link to solve error:
https://www.youtube.com/watch?v=8RYTriMo8EI&t=215s&ab_channel=ITTV

#
Author: Muhammad ijaz 




