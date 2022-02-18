# Ansible Collection - my_own_namespace


Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| test_path | "/tmp/test_01.txt" | Параметр, определяющий путь для нового файла, а также имя нового файла |
| test_content | "Test module in task\nHello, world!\n" | Строка, которая записывается в новый файл |


Example Playbook
----------------

---
- name: Test my_own_module in remote host
  hosts:
    - ubuntu
  roles:
    - my_role

