# Documento de Diseño del Juego - Ecos de la Penumbra

## 1. CONCEPTO CENTRAL

### Premisa
En un reino medieval sumergido en la decadencia, la "Penumbra" —una corrupción espiritual que devora la luz y distorsiona los recuerdos— ha consumido a reyes, santos y aldeanos por igual.

### Protagonista: El Resonante
- **Origen**: Antiguo caballero despojado de voz y memoria
- **Arma Principal**: Espada de hierro meteorítico
- **Poder Único**: Capacidad de absorber "ecos" (almas y recuerdos) de enemigos caídos
- **Mecánica Central**: Cada eco absorbido otorga poder pero también corrompe

---

## 2. PILARES DE DISEÑO

### A. Exploración
- Mundos interconectados con atajos desbloqueables
- Secretos ocultos en locaciones secundarias
- Fragmentos de historia dispersos en el entorno
- Atmósfera de descubrimiento constante

### B. Combate Metódico
- Ritmo pausado y deliberado
- Importancia del posicionamiento
- Sistema de parry/desvío como mecánica defensiva
- Vulnerabilidad a cambio de daño potenciado
- Ataques que generan estamina limitada

### C. Atmósfera Opresiva
- Iluminación dinámica y sombras profundas
- Sonido ambiental perturbador
- Enemigos diseñados para generar incomodidad
- Entornos que cuentan historias de ruina

---

## 3. MECÁNICAS PRINCIPALES

### Sistema de Combate
```
Controles Base:
- Ataque Rápido (tap)
- Ataque Fuerte (hold)
- Parry/Desvío (timing crítico)
- Esquiva (rol con invulnerabilidad breve)
- Uso de Eco (consumo de estamina especial)

Estamina:
- Se regenera lentamente fuera de combate
- Cada acción consume cantidad variable
- El parry exitoso regenera pequeña cantidad
- Bloqueo continuo es imposible
```

### Sistema de Ecos
```
Tipos de Ecos:
1. ECOS PASIVOS: Buffs permanentes (velocidad, resistencia)
2. ECOS ACTIVOS: Habilidades de combate (ataques especiales)
3. ECOS CORRUPTORES: Poderes oscuros con riesgo

Costo de Eco:
- Cada eco equipado aumenta barra de "Corrupción"
- Al 100% de corrupción: enemigos se adaptan
- Zona de riesgo: 75%+ de corrupción

Purificación:
- Derrotar jefes purifica ecos
- Bendichas locaciones reducen corrupción
- Sacrificar poder para evitar game over
```

### Progresión del Personaje
```
No hay XP tradicional. Progresión basada en:
1. DOMINIO DE COMBATE: Mejor timing = mejores resultados
2. COLECCIÓN DE ECOS: Acceso a nuevas habilidades
3. EQUIPAMIENTO: Espada mejora con descubrimientos
4. CONOCIMIENTO: Aprender patrones de enemigos
```

---

## 4. ESTRUCTURA DE NIVELES

### Patrones de Diseño

Cada nivel contiene:
- **1 Jefe Final**: Batalla épica que cierra el acto
- **3-5 Mini-Jefes**: Encuentros secundarios
- **Enemigos Comunes**: Variedad de tipos
- **Secretos**: 2-3 áreas ocultas por nivel
- **Puntos de Descanso**: Lugares seguros para recuperación

### Progresión de Dificultad
- Niveles 1-3: Tutorial velado (aprender mecánicas)
- Niveles 4-6: Aumento de complejidad (patrones nuevos)
- Niveles 7-9: Desafío máximo (enemigos potenciados)
- Niveles 10-11: Batalla contra el yo (reflexiones temáticas)
- Nivel 12: Enfrentamiento final (multifase)

---

## 5. JEFES Y ENCUENTROS EPICOS

### Jefe Final de Cada Acto

**Nivel 1: El Capitán Desfigurado**
- Tipo: Guerrero pesado
- Patrón: Cargas y bloqueos
- Eco: Resistencia aumentada

**Nivel 2: La Matriarca del Trazo**
- Tipo: Mago de rango
- Patrón: Proyectiles y teleportación
- Eco: Habilidad de proyectil mágico

**Nivel 3: El Inquisidor Ciego**
- Tipo: Híbrido rápido/fuerte
- Patrón: Ataques ciegos pero devastadores
- Eco: Aumento de velocidad crítica

**Nivel 6: El Gran Comendador Herido**
- Tipo: Jefe armadura pesada
- Patrón: Defensa sólida con contraataques
- Eco: Forma de lucha defensiva

**Nivel 9: El Obispo Olvidado**
- Tipo: Mago corrupto
- Patrón: Hechizos de área con demoras
- Eco: Maldición/buff de sombra

**Nivel 10: La Reina de Espinas**
- Tipo: Duelista de alta velocidad
- Patrón: Esgrima contra tu propio reflejo
- Eco: Espejo de movimiento

**Nivel 11: El Eco Primo (Tu Reflejo Oscuro)**
- Tipo: Clon perfecto de El Resonante
- Patrón: Copia exacta de tus movimientos
- Desafío: Combate psicológico

**Nivel 12: La Sombra del Reino (2 Fases)**
- **Fase 1**: Manifestación abstracta de la Penumbra
- **Fase 2**: Forma definitiva de la corrupción
- Recompensa: Verdadero final basado en ecos recolectados

---

## 6. SISTEMA DE FINALES MÚLTIPLES

### Rutas de Finalización

**Final Puro**: Derrotar La Sombra sin absorber más de 30% de ecos
- Cinemática: Restauración de la luz, El Resonante recupera voz
- Tono: Esperanzador pero melancólico

**Final Ambiguo**: 30-70% de ecos absorbidos
- Cinemática: La luz retorna pero la Penumbra sigue latente
- Tono: Victoria pero con costo

**Final Oscuro**: 70%+ de ecos absorbidos
- Cinemática: El Resonante se convierte en Nueva Penumbra
- Tono: Trágico, cíclico

---

## 7. ENEMIGOS Y TIPOS

### Jerarquía de Enemigos

**Clase Común**
- Guardias Decompuestos
- Cuervos de Peste
- Aldeanos Poseídos
- Perros Rabiosos
- Creyentes Olvidados

**Clase Especial**
- Bestias de Ceniza
- Esqueletos Armados
- Entidades de Ceniza Viva
- Arqueros Espectrales
- Gárgolas de Piedra Negra
- Caballeros de la Penumbra
- Magos de Plaga
- Harpías Corrompidas
- Abominaciones Anfibias
- Fuegos Fatuos
- Fanáticos Flagelantes
- Sombras Errantes

**Clase Elite** (Mini-Jefes)
- Versiones potenciadas de comunes
- Patrones de ataque únicos
- Derrotarlos purifica áreas

---

## 8. ESTÉTICA Y DIRECCIÓN ARTÍSTICA

### Paleta de Colores

**Dominantes**
- Grises: Piedra y ceniza
- Azules profundos: Noche y frío
- Violetas: Corrupción de la Penumbra

**Acentos**
- Naranjas cálidos: Fuego de antorchas
- Verdes bioluminiscentes: Magia corrompida
- Rojos sangre: Peligro inmediato

### Inspiración Visual
- Concept Art: Dark Souls, Blasphemous, Salt and Sanctuary
- Iluminación: Rembrandt y pintura de la Edad Media
- Arquitectura: Gótico tardío europeo

### Efectos Visuales Clave
- Partículas de luz/sombra en combate
- Deformaciones de pantalla en momentos de corrupción
- Transiciones entre luz y oscuridad
- Animaciones de absorción de ecos (vórtex visual)

---

## 9. BANDA SONORA Y AUDIO

### Estructura Musical

**Temas por Acto**
- Acto 1-3: Melancólico, esperanzador velado
- Acto 4-6: Desesperado, oscuro
- Acto 7-9: Aterrador, hipnótico
- Acto 10-12: Épico, conflictivo

### Sonidos Ambientales
- Viento constante según entorno
- Ecos de pasos en diferentes superficies
- Goteos en cuevas, lluvia en pueblos
- Murmullo de voces distantes (los caídos)
- Pulso rítmico (latido de la Penumbra)

### Sonidos de Combate
- Impactos de espada diferenciados
- Sonido de estamina consumiéndose
- Parry exitoso (sonido satisfactorio)
- Absorción de ecos (sonido alienígena/santo)

---

## 10. PROGRESIÓN DE HABILIDADES DESBLOQUEABLES

### Árbol de Habilidades (Sin Puntos - Solo Descubrimiento)

**Fase 1: Dominio Básico**
1. Ataque Fuerte
2. Parry
3. Esquiva

**Fase 2: Poderes Iniciales**
4. Eco Pasivo 1: Resistencia
5. Eco Activo 1: Corte Spinnning
6. Eco Pasivo 2: Velocidad

**Fase 3: Especialización**
7. Eco Corruptor 1: Golpe Sombrío
8. Eco Pasivo 3: Regeneración
9. Eco Activo 2: Onda de Choque

**Fase 4: Maestría**
10. Eco Supremo: Eco del Primer Rey
11. Forma Alternativa: Transformación Parcial
12. Eco Final: Absorber Todo

---

## 11. NARRATIVA Y STORYTELLING

### Narrativa Ambiental
- Objetos dispersos revelan historias
- Diálogos silenciosos (el protagonista no habla)
- Cinemáticas que no interrompen
- Flashbacks ambiguos de la memoria de El Resonante

### Temas Centrales
- La corrupción inevitable del poder
- La pérdida de identidad
- La naturaleza cíclica de la destrucción
- La redención vs. La rendición

### NPCs y Encuentros
- Pocos NPCs, pero memorables
- Cada uno representa una faceta de la Penumbra
- Diálogos sin opciones (narrativa lineal pero profunda)
- Encuentros que reflejan decisiones en ecos

---

## 12. MODOS DE JUEGO

### Campaña Principal
- 12 niveles progresivos
- Duración: 8-12 horas promedio
- New Game+ con dificultad aumentada

### Modo Desafío
- Encuentros específicos de jefes
- Limitaciones personalizables
- Tablas de puntuación

### Galería de Artes
- Desbloquear artworks
- Concept art comentado
- Música reproducible

---

## 13. PLATAFORMAS Y ESPECIFICACIONES TÉCNICAS

- **Motor**: Godot 4.x o Unity 2023+
- **Resolución Base**: 1920x1080 (escalable)
- **Framerate**: 60 FPS objetivo
- **Plataformas**: Windows, macOS, Linux (PC primario)
- **Futura Expansión**: Nintendo Switch, PlayStation, Xbox

---

## Documento Versión: 1.0
**Última actualización**: 2026-09-12
