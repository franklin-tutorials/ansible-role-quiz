Role : Quiz-Ansible
=========

Déploiement de l'application [Quiz-Ansible](https://github.com/franklin-tutorials/quiz-ansible)

Pré-requis
------------

Ce rôle est adapté pour fonctionner dans un environnement conteneurisé.

Les variables
--------------

```bash
serve_port: 3000
app_dir: /opt/quiz-ansible
```

Dependences
------------

Aucune.

Example Playbook
----------------

```bash
    - hosts: servers
      roles:
         - franklin-tutorials.quiz
```


License
-------

MIT

Author Information
------------------

Ftutorials
