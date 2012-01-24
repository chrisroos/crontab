desc 'Update crontab'
task :deploy, :hosts => 'jail0145.vps.exonetric.net' do
  run "mkdir -p /home/chrisroos/tmp"
  upload 'crontab.txt', '/home/chrisroos/tmp/crontab.txt'
  run "crontab /home/chrisroos/tmp/crontab.txt"
end