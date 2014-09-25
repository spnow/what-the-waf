Is there a WAF? Go terrorize it!  
-- A Burp 1.6+ Extension  

#Features
1. Advanced options to pentest worldclass WAFs  
2. Sophisticated payloads  
3. Save test resluts and draw a chart from them  
4. Empowers the mighty Burp  

#Installation
Download jruby-complete jar file from [JRuby](http://www.jruby.org/download)  
Open the "Burp Suite"  
Go to "Extender"  
Go to "Options"  
On "Ruby Environment" section set the "Location of JRuby JAR file" to   "\[foo\]/\[bar\]/jruby-complete-\[version\].jar"  
Go to "Extensions"  
Click "Add"  
Set "Extension Type" to "Ruby"  
Click "Select File" and choose "\[foo\]/\[bar\]/what-the-waf.rb"  

# Case Study and Examples
### example/General
WTW 101  

### example/Fortiweb
Configure Burp and WTW to pentest a FortiWeb WAF (real-world case-study)  

### example/Chart
How to draw a chart from a saved result  

# Usage
Please take a look at "Readme" tab in the "What the WAF?!" extension tab in Burp.  
You can find useful informations about how to use WTW and what are its limitations.  

#Test Environment
jruby-complete.jar Version: 1.7.15  
local jruby version: 1.5.6  
OS: Debian Jessie  

