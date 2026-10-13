# Mi servidor Mineclonia

- Juego: Mineclonia
- Modo: supervivencia/anarquia
- Maximo: 20 jugadores
- Puerto: UDP 30000
- Configuracion: server/minetest.conf
- Mundo persistente: server/worlds/world

## Iniciar
docker compose up -d

## Ver registros
docker compose logs -f mineclonia

## Detener
docker compose stop mineclonia

## Reiniciar
docker compose restart mineclonia
