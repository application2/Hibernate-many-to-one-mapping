<?xml version="1.0" encoding="UTF-8"?>
<web-app xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://java.sun.com/xml/ns/javaee" xmlns:web="http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" xsi:schemaLocation="http://java.sun.com/xml/ns/javaee http://java.sun.com/xml/ns/javaee/web-app_2_5.xsd" id="WebApp_ID" version="2.5">
  <display-name>hibernatemanytoonemapping</display-name>
  <welcome-file-list>
    <welcome-file>index.jsp</welcome-file>
  </welcome-file-list>
  <servlet>
    <description>This servlet is to add persons along with their address</description>
    <display-name>AddPersonServlet</display-name>
    <servlet-name>AddPersonServlet</servlet-name>
    <servlet-class>com.servlet.AddPersonServlet</servlet-class>
  </servlet>
  <servlet-mapping>
    <servlet-name>AddPersonServlet</servlet-name>
    <url-pattern>/add</url-pattern>
  </servlet-mapping>
</web-app>
