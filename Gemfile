source ENV['GEM_SOURCE'] || 'https://rubygems.org'

gem 'facter', '>= 1.7.0'
gem 'guard-rake'
gem 'metadata-json-lint'
gem 'puppet', '>= 4.10.1'
gem 'puppet-lint', '>= 1.0.0'
gem 'puppet-strings'
gem 'puppetlabs_spec_helper', '>= 1.0.0'
gem 'rspec-puppet'
gem "github_changelog_generator",                    require: false, git: 'https://github.com/skywinder/github-changelog-generator', ref: '20ee04ba1234e9e83eb2ffb5056e23d641c7a018' if Gem::Version.new(RUBY_VERSION.dup) >= Gem::Version.new('2.2.2')
gem 'puppet-blacksmith'

gem 'beaker'
gem 'beaker-puppet_install_helper'
gem 'beaker-module_install_helper'
gem 'beaker-testmode_switcher'
gem 'beaker-rspec'
gem 'serverspec'

gem 'rake'
gem 'rubocop', '= 0.49.1'
gem 'rubocop-rspec', '= 1.15.1'

# Debugging
gem 'pry'                # Pry Debugger: Console driven debugger.  Stops the execution in the middle of a call to allow inspection of ruby variables
gem 'pry-byebug'         # Pry Plugin: used to step through the code
gem 'pry-stack_explorer' # Pry Plugin: used to step through the code.  Shows how you got to where you are now and the variables at each point in the stack
gem 'pry-rescue'