forge "http://forge.puppetlabs.com"

mod 'puppetlabs/apt'
mod 'puppetlabs/firewall'
mod 'puppetlabs/mysql'
mod 'puppetlabs/ntp'
mod 'puppetlabs/stdlib'

mod 'ripienaar/concat'


mod 'rtyler/puppet'


mod 'sshd', :git => 'git://github.com/jenkinsci/puppet-sshd.git'
mod 'postgres', :git => 'git://github.com/jenkinsci/puppet-postgres.git'

# Pull in all our local modules automatically
Dir["./local-modules/*"].each do |path|
  mod File.basename(path), :path => path
end


# vim: ft=ruby
