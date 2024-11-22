registo
curl -X POST http://localhost:3000/register \
-H "Content-Type: application/json" \
-d '{
      "name": "vitormarcker",
      "email": "vitormarcker@example.com",
      "password": "Vitormarcker@123"
    }'

login
curl -X POST http://localhost:3000/login \
-H "Content-Type: application/json" \
-d '{
      "email": "vitormarcker@example.com",
      "senha": "Vitormarcker@123"
    }'