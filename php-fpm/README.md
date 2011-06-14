# Synopsis

Ganglia check script for PHP-FPM

# Dependencies

  - PHP 5+
  - Ganglia, installed and configured

# Installation

  - Set 'pm.status_path' to '/fpm_status'
  - Place both scripts in a suitable location on server, set executable bit on php-fpm script
  - Update php-fpm script if using non-standard host/port
  - Test execution of php-fpm
  - Create cron entry to execute php-fpm script (at minute intervals recommended)
