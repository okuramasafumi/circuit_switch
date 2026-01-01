source "https://rubygems.org"

# Specify your gem's dependencies in circuit_switch.gemspec
gemspec

gem "appraisal"
gem "rake", "~> 13.0"

rails_version = ENV['RAILS_VERSION']
if rails_version
  version = "~> #{rails_version}"
  %w[activejob activerecord activesupport].each do |gem_name|
    gem gem_name, version
  end
end
