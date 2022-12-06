![DK photo](photo-acc.jpg)

### Denis Korolev
_ devsboom@gmail.com_
** junior web developer **

_A junior web developer willing to grow as a full-stack specialist. With 1 year of
hand-on experience in developing & deploying web apps using Python web frameworks.
Studying new technologies and looking further to successful career by working for an
ambitious company._

**SKILLS & ABILITIES**
* HTML
* CSS
  * Bootstrap
* JavaScript
  * Vue.js
* Python
  * Django + DRF
* SQL
* Docker
  * Docker Compose
* Git
* Nginx
* uWSGI
* Linux

__AUG 2022 – PRESENT
Web Application Developer
Developing backends, RESTful APIs and Telegram-bots for web
apps using Python (Django, Django REST framework, Flask).
Administrating Ubuntu server and deploying web apps using
Nginx , uWSGI servers. Working in a small team on the web
service for business automation and accounting reports
(Transportation industry)__

#### Code example:
```
class SomeView(APIView):

    def get(self, request, pk):
        model_1 = Model1.objects.filter(id=pk).select_related('owner').values().first()
        model_2 = Model2.objects.filter(id=model_1['owner_id']).first()
        if not model_1:
            return Response({'error': "Персонал сайта"}, status=status.HTTP_403_FORBIDDEN)
        fields = model_2.objects.filter(model_2__id=card['id']).values()
        some_1= None
        some_2 = None
        img_path = model_1['photo']
        if img_path != '':
            image_path = '/root/folder1/' + model_1['photo']
            with open(f"{image_path}", "rb") as img_file:
                img_string = base64.b64encode(img_file.read())
                img = img_string.decode('utf-8')
                img_type = magic.from_file(image_path, mime=True)
                data = img_type.split('/')[1].upper()
                image = f'TYPE={data}:{img}'
        for field in fields:
            if field['title'] == 'some_1':
                some_1 = field['link'][4:]
                break
        if phone is None:
            try:
                if model_1.usercontactinfo.contact_type == 0:
                    some_2 = model_1.info.contactinfo
            except:
                return Response({'some_1': model_1}, status=status.HTTP_200_OK)
        return Response({'some_1': model_1}, status=status.HTTP_200_OK)
```
### EDUCATION
**ITMO UNIVERSITY, ST.PETERSBURG, RUSSIA, WEB DEVELOPER**
[Graduation project](https://github.com/KD3821/email_chimp)

### ENGLISH (B1)