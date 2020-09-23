require 'html-proofer'

desc 'check for broken links'
task :test do
  opts = {
    check_external_hash: true,
    allow_hash_href: true,
    assume_extension: true,
    check_html: true,
    disable_external: true,
    empty_alt_ignore: true,
    only_4xx: true,
    verbose: true
  }
  HTMLProofer.check_directory('./_site', opts).run
end
