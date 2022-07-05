### Playbook для запуска Clickhouse + Vector + Lighthouse

1. Загрузить роли:

```bash
ansible-galaxy role install --role-file requirenments.yml
```

2. Запустить playbook:

```bash
ansible-playbook -i inventory/prod.yml site.yml
```

