Vagrant.configure('2') do |config|
  config.vm.box = 'cloudfoundry/bosh-lite'

  config.vm.provider :virtualbox do |v, override|
    override.vm.box_version = '9000.130.0'
  end
end
