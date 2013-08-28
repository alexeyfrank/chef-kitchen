site :opscode

cookbook 'apt'

cookbook 'postgresql'
cookbook 'mysql'
cookbook 'database'
cookbook 'nodejs'

cookbook 'perl'
cookbook 'redisio'
cookbook 'users'
cookbook 'zsh'
cookbook 'phantomjs'

cookbook 'nginx', '~> 0.101.5'

cookbook 'locale',
  :git => 'git://github.com/deepak/chef-locale.git', :branch => "deepak/bugfix/set-language"

cookbook 'sphinxsearch', git: 'git://github.com/devops-israel/chef-sphinxsearch.git'
cookbook 'imagemagick', git: 'https://github.com/opscode-cookbooks/imagemagick'

cookbook 'rvm',
  # Use this fork because original have no autolibs support
  :git => 'git://github.com/ballistiq/chef-rvm.git', :branch => 'e5acdeb552b6ad18d6d4a212a1671e8145d65bbe'
