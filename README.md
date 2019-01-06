For demo run:
1.1) make sure that jetty plugin is uncommented in pom.xml
1.2) make sure that in users_check_page.jsp in 'form' action="/users-system/users/check"
2) create Maven configuration with 'Command line':
clean package jetty:run
3) run configuration
4) check endpoints:
http://localhost:9999/users-system - to see greeting page
http://localhost:9999/users-system/users/list - for users list
http://localhost:9999/users-system/users/validate - for users validation: admin + admin -> valid, others - invalid