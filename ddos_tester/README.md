Setup
=====

 * Make sure Ruby 1.9 is installed
 * Run from the command-line 

 	gem install bundler
 	
 * Then run 

 	bundle install


Usage
-----
 * Modify example.yaml to add in the URLs you wish to attack
 * Run the ddos_tester like example below

	ruby ddos_tester.rb &lt;YAML_FILE_HOLDING_URLS&gt; &lt;MAX_CONCURRENCY&gt;[1-200 optional] 