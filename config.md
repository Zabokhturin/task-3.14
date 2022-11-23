[ < К содержанию](./readme.md)

## git config
---
Если вы только установили Git, то нужно будет настроить 2 переменные: user.name и user.email - это подписи коммитов. По ним будет ясно, кто вносил правки в код. Не путайте эти настройки с настройками, которые вы указывали на Github, они не имеют никакого к ним отношения.

```bash-
git config --global user.name "Your Name" .

git config --global user.email "your_email@whatever.com ."