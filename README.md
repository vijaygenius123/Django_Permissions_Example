from django.contrib.auth.models import User

User.objects.all()[1].groups.values_list('name')
