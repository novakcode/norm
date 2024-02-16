Currently getting `ExceptionInInitializerError` 

Only way to bypass this was to add

**--add-opens=java.base/java.lang=ALL-UNNAMED** to VM arguments


