appraise 'activerecord-5.2' do
  case ENV["DB"]
  when "postgresql"
    gem 'pg'
  when "mysql"
    gem 'mysql2', '~> 0.3'
  else
    gem 'sqlite3'
  end
  gem 'activerecord', '~> 5.2.0'
end

appraise 'activerecord-5.1' do
  case ENV["DB"]
  when "postgresql"
    gem 'pg'
  when "mysql"
    gem 'mysql2', '~> 0.3'
  else
    gem "sqlite3", "~> 1.3.6"
  end
  gem 'activerecord', "~> 5.1.1"
end

appraise 'activerecord-5.0' do
  case ENV["DB"]
  when "postgresql"
    gem 'pg'
  when "mysql"
    gem 'mysql2', '~> 0.3'
  else
    gem "sqlite3", "~> 1.3.6"
  end
  gem 'activerecord', "~> 5.0.3"
end

appraise 'activerecord-6.0' do
  case ENV["DB"]
  when "postgresql"
    gem 'pg'
  when "mysql"
    gem 'mysql2', '~> 0.3'
  else
    gem 'sqlite3'
  end
  gem 'activerecord', "~> 6.0.0.rc1"
end
