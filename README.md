<img src="https://i.imgur.com/OqX1bEi.png" height="220" alt="Spreader" align="right">

<div align="center">

## Spreader

Spreader es un plugin que permite teletransportar jugadores a posiciones específicas.
</div>

## 📥Comandos Disponibles

### `/savespawn`
- **Descripción**: Guarda tu posición actual para el teletransporte
- **Permisos**: `spreader.savespawn`
- **Uso**: Simplemente ejecuta el comando donde quieras guardar la posición

### `/spreader`
- **Descripción**: Teletransporta jugadores a las posiciones guardadas en orden
- **Permisos**: `spreader.spreader`
- **Uso**: Ejecuta el comando para teletransportar todos los jugadores (excepto operadores) a las posiciones guardadas

### `/listpositions`
- **Descripción**: Lista todas las posiciones guardadas
- **Permisos**: `spreader.listpositions`
- **Uso**: Muestra todas las posiciones guardadas con sus coordenadas

### `/clearpositions`
- **Descripción**: Elimina todas las posiciones guardadas
- **Permisos**: `spreader.clearpositions`
- **Uso**: Limpia todas las posiciones guardadas

### `/testposition`
- **Descripción**: Permite a operadores probar posiciones una por una
- **Permisos**: `spreader.testpositions`
- **Uso**: 
  - `/testposition` - Muestra todas las posiciones disponibles
  - `/testposition <número>` - Teletransporta al operador a la posición específica

### `/spreaderinfo`
- **Descripción**: Muestra información detallada del plugin
- **Permisos**: `spreader.info`
- **Uso**: `/spreaderinfo` - Muestra estado del plugin, estadísticas y comandos disponibles

## 📦Cómo Usar

1. **Guardar Posiciones**: 
   - Ve a las ubicaciones donde quieres teletransportar jugadores
   - Ejecuta `/savespawn` en cada ubicación
   - Las posiciones se guardan en el orden que las guardes

2. **Teletransportar Jugadores**:
   - Ejecuta `/spreader`
   - Los jugadores serán teletransportados en orden a las posiciones guardadas
   - Los (OP) serán ignorados automáticamente

3. **Gestionar Posiciones**:
   - Usa `/listpositions` para ver todas las posiciones guardadas
   - Usa `/clearpositions` para eliminar todas las posiciones
   - Usa `/testposition` para probar posiciones como operador
   - Usa `/spreaderinfo` para ver información del plugin

## ⚙️ Características

- ✅ Teletransporte automático ignorando op
- ✅ Sistema de posiciones en orden
- ✅ Mensajes informativos

## 📜Permisos

Todos los comandos requieren permisos específicos:
- `spreader.savespawn` - Para guardar posiciones
- `spreader.spreader` - Para teletransportar jugadores
- `spreader.listpositions` - Para listar posiciones
- `spreader.clearpositions` - Para eliminar posiciones
- `spreader.testpositions` - Para probar posiciones como operador
- `spreader.info` - Para ver información del plugin

Por defecto, todos los permisos están configurados para op (`default: op`).

## 🧪Ejemplo de Uso

1. Vas a diferentes ubicaciones y usas el comando `/savespawn` para guardar la posicion
2. Cuando esté listo, ejecuta `/spreader`
3. Los jugadores son teletransportados automáticamente a las posiciones en orden

## ⚖️ Licencia
Spreader está licenciado bajo la Licencia MIT. Puedes encontrar la licencia [aqui](LICENSE).


## Almacenamiento de Posiciones

Las posiciones se guardan automáticamente en el archivo `plugins/Spreader/positions.yml`
