# Canchas

**POST http://localhost:8081/canchas**

```javascript
{
    "nombreCancha": "Cancha 1",
    "tipoCancha": "Pasto sintético",
    "estadoCancha": "Disponible",
    "precioCancha": 3000
}
```
```javascript
{
    "nombreCancha": "Cancha 2",
    "tipoCancha": "Pasto real",
    "estadoCancha": "Disponible",
    "precioCancha": 7000
}
```

**GET http://localhost:8081/canchas/2**

**GET http://localhost:8081/canchas**

---

# Reservas

**POST http://localhost:8082/reservas**

```javascript
{
  "idCancha": 1,
  "cliente": "Ema Miau",
  "fecha": "2026-03-13",
  "horario": "10:00 - 11:00"
}
```

```javascript
{
  "idCancha": 1,
  "cliente": "Juno Miau",
  "fecha": "2026-03-13",
  "horario": "11:00 - 12:00"
}
```

```javascript
{
  "idCancha": 2,
  "cliente": "Dante Miau",
  "fecha": "2026-03-13",
  "horario": "10:00 - 11:00"
}
```

**GET http://localhost:8082/reservas/2**

**GET http://localhost:8081/canchas**

**GET http://localhost:8082/reservas/cancha/1**

