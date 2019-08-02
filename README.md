# Introduction

This example shows you how to protect your class based views and function based views with role/group based access

To list all the groups a user belongs to run the command below from Django shell

    from django.contrib.auth.models import User
    User.objects.all()[1].groups.values_list('name')
