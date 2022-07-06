Ansible Role: oVirt VM Delete
=========

Эта роль удалит виртуальную машину в системе управления виртуализацией oVirt.

Requirements
------------

Для хоста, на котором запускается эта роль необходимы следующие требования:
```
python >= 2.7
ovirt-engine-sdk-python >= 4.3.0
```

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию в файле **defaults/main.yml**.
Для создания HTTP/HTTPS-соединения с порталом администрирования oVirt необходимо задать переменные для аутентификации:
```
ovirt_auth_url:
ovirt_auth_user:
ovirt_auth_password:
ovirt_auth_cafile:
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ovirt_vm_delete

License
-------

BSD

Author Information
------------------

Chubik Sergey.
