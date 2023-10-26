<h1>Install Varnish Cache Magento</h1>
<ol>
  <li>sudo apt-get install varnish</li>
  <li>
      Change port 6082 => 80. 
      sudo nano /lib/systemd/system/varnish.service
  </li>
  <li>
      Change port 6082 => 80. 
      sudo nano /etc/default/varnish
  </li>
   <li>
      copy text from default.vcl to file etc/varnish/default.vcl
  </li>
  <li>
     change port default apache2 (Listen 8080)
     sudo nano /etc/apache2/ports.conf
  </li>
  <li>
     change port host web  (Listen 8080)
     sudo nano /etc/apache2/sites-available/{file}
  </li>
</ol>
