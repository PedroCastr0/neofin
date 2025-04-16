# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in neofin.gemspec
gemspec

# Grupo de dependências usadas apenas durante o desenvolvimento e teste
group :development, :test do
  gem "irb"
  gem "rubocop", "~> 1.21"
  # Minitest é a biblioteca padrão de testes do Ruby
  gem "minitest", "~> 5.16"
  # Rake permite definir e rodar tarefas (como executar testes)
  gem "rake", "~> 13.0"
  # WebMock ajuda a simular requisições HTTP nos testes, para não depender da API real
  gem "webmock", "~> 3.25.1"
  # Dotenv carrega variáveis de ambiente de um arquivo .env (útil para guardar API keys localmente)
  gem "dotenv", "~> 3.1.8"
end
