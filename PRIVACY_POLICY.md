# Política de Privacidad — BIOMEK Coach

**Última actualización:** [FECHA]
**Contacto:** support.biomek@gmail.com

BIOMEK Coach ("la app") es una aplicación de entrenamiento de fuerza. Esta política describe qué datos recopilamos, cómo se usan y cuáles son tus derechos.

## 1. Datos que recopilamos

### 1.1 Datos que tú proporcionas
- **Cuenta (opcional):** dirección de correo electrónico y contraseña, si creas una cuenta en la nube.
- **Datos de entrenamiento:** historial de sesiones, ejercicios, series, repeticiones, cargas, RPE, notas de sesión y récords personales.
- **Perfil de atleta:** nivel de experiencia, días disponibles, equipamiento, lesiones reportadas, metas declaradas, unidad de peso preferida y mediciones corporales (peso, cintura, etc.) que registres voluntariamente.
- **Rutinas personalizadas** que crees o edites.

### 1.2 Datos recopilados automáticamente
- **Datos de suscripción:** RevenueCat procesa el estado de tu suscripción Pro (entitlement, historial de compra) usando un ID de usuario anónimo que se vincula a tu cuenta si creas una.
- **Datos técnicos mínimos:** la app no recopila analytics de comportamiento ni publicidad. No usamos Firebase Analytics, Facebook SDK ni rastreadores de terceros.

### 1.3 Datos que NO recopilamos
- No accedemos a tu cámara, micrófono, contactos, ubicación ni archivos.
- No vendemos datos a terceros. No mostramos anuncios.

## 2. Dónde se almacenan los datos

- **Localmente (primario):** todos los datos de entrenamiento se guardan primero en tu dispositivo (SharedPreferences). La app funciona 100% sin cuenta ni internet.
- **Nube (opcional):** si creas una cuenta, tus datos se sincronizan a Supabase (PostgreSQL en la nube, región Canadá Central) para respaldo y uso multi-dispositivo. Cada fila está protegida por Row Level Security: solo tu cuenta puede leer o escribir tus datos.
- **Suscripciones:** RevenueCat (EE.UU.) gestiona el estado de compra. Consulta su política en https://www.revenuecat.com/privacy.

## 3. Para qué usamos los datos

- Generar y ajustar tu programa de entrenamiento (bloques, cargas, deloads, sustituciones por lesión).
- Mostrar tu historial, progreso y récords.
- Respaldar y sincronizar tus datos entre tus dispositivos.
- Verificar el estado de tu suscripción Pro.

No usamos tus datos para publicidad, perfiles comerciales ni los compartimos con terceros fuera de los proveedores listados (Supabase, RevenueCat, tiendas de apps para pagos).

## 4. Retención y eliminación

- Los datos locales viven en tu dispositivo hasta que desinstales la app o uses "Borrar todos los datos" en Ajustes.
- Los datos en la nube se conservan mientras tu cuenta exista. Puedes eliminarlos permanentemente desde Ajustes → Cuenta → "Eliminar cuenta y datos" (borra todas las filas asociadas a tu user_id en Supabase) o escribiéndonos a support.biomek@gmail.com.
- Los registros de suscripción en RevenueCat pueden conservarse por requisitos fiscales de las tiendas, sin datos de entrenamiento.

## 5. Seguridad

- Contraseñas: gestionadas por Supabase Auth (hash bcrypt, nunca en texto plano).
- Comunicación: HTTPS en todas las llamadas a Supabase y RevenueCat.
- Acceso a datos: Row Level Security en cada tabla — ningún usuario puede leer datos de otro.
- La clave "publishable" embebida en la app solo permite operaciones sobre tus propios datos; la clave maestra nunca se distribuye.

## 6. Menores de edad

La app está dirigida a mayores de 16 años (o la mayoría de edad digital de tu jurisdicción). No recopilamos conscientemente datos de menores.

## 7. Tus derechos

Dependiendo de tu jurisdicción (GDPR, LFPDPPP, etc.) puedes:
- Acceder a tus datos (Ajustes → Exportar mis datos genera un JSON completo).
- Rectificarlos editándolos en la app.
- Eliminarlos (borrado local + eliminación de cuenta).
- Exportarlos en formato legible (JSON).
- Retirar el consentimiento cerrando sesión y borrando la cuenta.

## 8. Cambios a esta política

Publicaremos cambios materiales dentro de la app y actualizaremos la fecha de "última actualización".

## 9. Contacto

support.biomek@gmail.com

---

*English summary: BIOMEK Coach stores training data locally first; optional cloud sync via Supabase (RLS-protected); subscriptions via RevenueCat; no ads, no tracking, no data sale. Data export and deletion are available in-app. Full Spanish text above is the canonical version.*
