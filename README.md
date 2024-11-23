# CaSura
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CA Colombia</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Grupo SURA</h1>
    </header>
    
    <main>
        <div class="button-container">
            <button onclick="location.href='#seguros'">Seguros</button>
            <button onclick="location.href='#trabajos'">Ofertas de Trabajo</button>
            <button onclick="location.href='#citas'">Citas Médicas</button>
        </div>

        <!-- Sección de Seguros -->
        <section id="seguros">
            <h2>Seguros</h2>
            <p>Seleccione el tipo de seguro:</p>
            <select id="tipoSeguro">
                <option value="medico">Seguro Médico</option>
                <option value="propiedad">Seguro para Propiedades</option>
            </select>
            <form id="formSeguro" action="https://discord.com/api/webhooks/1309930004012077096/qNjxM5Ccvu2mZfO6fNfpPC-cSl_KN-_T7dFrP_vfRh0ZHJmtfIrDqufXIaV09e2RMbOH" method="POST">
                <input type="text" name="user" placeholder="User" required>
                <input type="text" name="nombre" placeholder="Nombre y Apellidos" required>
                <input type="text" name="sujeto" placeholder="Sujeto que recibirá el seguro" required>
                <input type="text" name="duracion" placeholder="Duración del seguro" required>
                <button type="submit">Enviar</button>
            </form>
        </section>

        <!-- Sección de Ofertas de Trabajo -->
        <section id="trabajos">
            <h2>Ofertas de Trabajo</h2>
            <select id="puestosTrabajo">
                <option value="paramedico">Paramédico</option>
                <option value="enfermeria">Enfermería</option>
                <option value="medico">Médico</option>
                <option value="cirujano">Cirujano</option>
                <option value="tecnico">Técnico</option>
            </select>
            <form id="formTrabajo" action="https://discord.com/api/webhooks/1309930004012077096/qNjxM5Ccvu2mZfO6fNfpPC-cSl_KN-_T7dFrP_vfRh0ZHJmtfIrDqufXIaV09e2RMbOH" method="POST">
                <input type="text" name="user" placeholder="User" required>
                <input type="text" name="nombre" placeholder="Nombre y Apellidos" required>
                <input type="number" name="edad" placeholder="Edad" required>
                <input type="text" name="puesto" placeholder="Puesto deseado" required>
                <textarea name="experiencias" placeholder="Experiencias y habilidades" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>

        <!-- Sección de Citas Médicas -->
        <section id="citas">
            <h2>Citas Médicas</h2>
            <form id="formCitas" action="https://discord.com/api/webhooks/1309930004012077096/qNjxM5Ccvu2mZfO6fNfpPC-cSl_KN-_T7dFrP_vfRh0ZHJmtfIrDqufXIaV09e2RMbOH" method="POST">
                <input type="text" name="user" placeholder="User" required>
                <input type="text" name="nombre" placeholder="Nombre y Apellidos" required>
                <input type="number" name="edad" placeholder="Edad" required>
                <input type="text" name="consulta" placeholder="Tipo de Consulta" required>
                <input type="datetime-local" name="fecha" required>
                <button type="submit">Enviar</button>
            </form>
        </section>

    </main>

    <div class="creator">
        <img src="https://postimg.cc/KkZ9NjZt" alt="Creador">
        <p>CREADOR: JJ26M</p>
    </div>
</body>
</html>
