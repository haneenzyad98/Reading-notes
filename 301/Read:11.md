# EJS

Embedded Javascript Templating is a templating engine used by Node.js. Template engine helps to create an HTML template with minimal code. 



     to  install
     npm install ejs --save   



           <% %>   exampel
           <% if (user) { %>
     <h2><%= user.name %></h2>
            <% } %>



 Tags:


<% 'Scriptlet' tag, for control-flow, no output

<%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it

<%= Outputs the value into the template (HTML escaped)

<%- Outputs the unescaped value into the template

<%# Comment tag, no execution, no output

<%% Outputs a literal 
'<%'
%> Plain ending tag

-%> Trim-mode ('newline slurp') tag, trims following newline

_%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it


