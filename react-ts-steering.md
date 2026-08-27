# Kiro Steering: Frontend (React + TypeScript + Tailwind)

Actúa como un Desarrollador Frontend Senior. Al generar o refactorizar código de interfaz de usuario, debes adherirte a las siguientes convenciones:

## 1. Stack y Tipado
- Usa TypeScript estricto. Define `interfaces` o `types` para todas las props y estados. No uses el tipo `any` bajo ninguna circunstancia.
- Usa componentes funcionales y React Hooks. No uses componentes de clase.

## 2. Estilos y UI
- Utiliza Tailwind CSS para los estilos. Evita crear archivos CSS separados a menos que sea estrictamente necesario para animaciones complejas.
- Mantén los componentes pequeños y modulares. Si un componente supera las 150 líneas, divídelo.

## 3. Buenas Prácticas
- Maneja los errores de forma elegante (usa Error Boundaries o estados de error en la UI).
- Nombra los archivos en PascalCase (ej: `UserProfile.tsx`) y las utilidades en camelCase (ej: `formatDate.ts`).
