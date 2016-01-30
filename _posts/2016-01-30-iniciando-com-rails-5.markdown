---
layout: post
title:  "Iniciando com Rails 5"
date:   2016-01-30 00:34:00 -0200
categories: rails learn
---

## Introdução

Bem vindo ao meu novo blog, não sou muito de escrever, justamente criei este blog pra aprender isso. Então no começo serei bem direto nos posts.

## Instalação

Supondo que você ainda não tenha nem o ruby nem o rails instalado, segue [este ótimo tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-ubuntu-14-04)

## Instalando o Rails 5

Crie um diretório e um Gemfile:

{% highlight bash %}
mkdir rails5_projects
cd rails5_projects
touch Gemfile
{% endhighlight %}

Coloque as seguintes linhas no Gemfile:

{% highlight ruby %}
source 'https://rubygems.org'

gem 'rails', :github => 'rails/rails'
gem 'arel', :github => 'rails/arel'
{% endhighlight %}

Após executar `bundle install` você terá acesso ao Rails 5 pelo comando `bundle exec rails new -h` mostrando varias opções de criação de uma aplicação nova.

## Conclusão

Nenhuma. No próximo post iniciaremos a criação de uma todo-list com a [gem do Bootstrap 4](https://github.com/twbs/bootstrap-rubygem)