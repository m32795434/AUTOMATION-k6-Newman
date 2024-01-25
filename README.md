## Practicing a little with K6 and Newman

### Inside the K6 folder run:

"k6 run k6-GET-POST-Stress-Test-Bravard-Manuel.js"

This will run an automated testing (Stress imitation testing)

### Inside the API folder, run:

"newman run Ejercitacion-postman-mod5.postman_collection.json -e Entorno-de-pruebas-Ejercitacion-Postman.postman_environment.json -r htmlextra"

This will create a new folder named "newman". Inside this folder you will have a summary about an Api automated testing.
