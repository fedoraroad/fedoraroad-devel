# Fedora Road Devel

## Установка окружения для работы.

* Устанавливаем [rbenv](https://github.com/rbenv/rbenv/blob/master/README.md#installation)
* Устанавливаем [ruby-build](https://github.com/rbenv/ruby-build#installation)
* Устанавливаем зависимости, для сборки ruby

Для debian-based

```bash
sudo apt install -y libssl-dev zlib1g-dev libreadline6-dev
```

Для fedora
```bash
sudo dnf -y install bzip2 gcc readline-devel zlib-devel openssl-devel
```

* Устанавливаем (компилим) руби.
```bash
rbenv install 2.2.5
rbenv global 2.2.5
```
* Устанавливаем гем менеджер
```bash
gem install bundler
```
cd в папку проекта.
```bash
bundle
```
Теперь остаётся только запустить лайв сервер
```Bash
jekyll serve --port 8080
```
