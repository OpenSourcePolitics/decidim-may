# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable-updated"
# gem "decidim", path: "../decidim"

gem "decidim-consultations", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable-updated"
gem "decidim-initiatives", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable-updated"

# gem "decidim-consultations", path: "../decidim"
# gem "decidim-initiatives", path: "../decidim"


# gem "decidim-participations", git: "https://github.com/OpenSourcePolitics/decidim-participations.git", branch: "09-stable"
# gem "decidim-export", git: "https://github.com/OpenSourcePolitics/decidim-user-export.git"

# Uncomment the following line if you want to use decidim-assemblies plugin
# gem "decidim-assemblies", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable-updated"

gem "bootsnap", "~> 1.3"

gem "puma", "~> 3.0"
gem "uglifier", ">= 1.3.0"
gem "faker", "~> 1.8.4"

gem "loofah" , "~> 2.2.1"
gem "nokogiri", "~> 1.8.2"
gem "rails-html-sanitizer", "~> 1.0.4"
gem "sinatra", "~> 2.0.2"
gem "sprockets", "~> 3.7.2"

group :development, :test do
  gem "pry-byebug", platform: :mri

  gem "decidim-dev", git: "https://github.com/OpenSourcePolitics/decidim.git", branch: "0.12-stable-updated"
  # gem "decidim-dev", path: "../decidim"
end

group :development do
  gem "letter_opener_web", "~> 1.3.0"
  gem "listen", "~> 3.1.0"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console"
end

group :production do
  gem 'passenger'
  gem 'fog-aws'
  gem 'dalli'
  gem 'sendgrid-ruby'
  gem 'newrelic_rpm'
  gem 'lograge'
  gem 'sentry-raven'
  gem 'sidekiq'
end
