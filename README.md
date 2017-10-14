<h1>Hosts para Elementt Phone Flash II (2) ES_F661 ESF661COCA1</h1>

<p>Este repositorio contiene archivos hosts que est&aacute;n creados con el prop&oacute;sito de bloquear la publicidad que aparece repentinamente en el tel&eacute;fono Elementt Flash II vendido exclusivamente en Chile y que afecta el uso cotidiano del dispositivo.​​</p>

<ul>
	<li>&Uacute;ltima actualizaci&oacute;n: <strong>14-10-2017</strong></li>
</ul>

<h2>Gu&iacute;a de instalaci&oacute;n</h2>

<p><strong>Importante,&nbsp;descargo de responsabilidad: No me hago responsable por los da&ntilde;os o efectos que pueda tener este procedimiento en el software o hardware de tu equipo. Hazlo bajo tu propia responsabilidad.</strong></p>

<h3>Requerimientos</h3>

<ul>
	<li>Tel&eacute;fono Elementt Flash II&nbsp;ES_F661.</li>
	<li>Conexi&oacute;n a internet en el dispositivo.</li>
	<li>Opci&oacute;n de instalaci&oacute;n de aplicaciones desde fuentes desconocidas activada en el equipo (Configuraci&oacute;n - Seguridad).</li>
	<li>Aplicaci&oacute;n de Android capaz de crear una conexi&oacute;n VPN local con posibilidad de agregar archivos hosts que est&eacute;&nbsp;<u>instalada</u>&nbsp;en el tel&eacute;fono, para efectos de esta gu&iacute;a utilizaremos <a href="https://github.com/M66B/NetGuard" target="_blank">NetGuard</a> que se puede descargar gratuitamente desde <a href="https://github.com/M66B/NetGuard/releases" target="_blank">aqu&iacute;</a>&nbsp;(NetGuard-vX.XXX-all-release.apk)</li>
</ul>

<h3>Instalaci&oacute;n</h3>

<p>Pueden parecer muchos pasos pero es para presentarlo con lujo de detalle y as&iacute; reducir la cantidad de problemas en la instalaci&oacute;n.</p>

<p>Nota: Verificar que no tienes otra aplicaci&oacute;n VPN, cortafuegos, firewall, proxy, antivirus, anti-malware&nbsp;o similar instalada en el dispositivo ya que podr&iacute;a entrar en conflicto con la que usaremos para esta gu&iacute;a.</p>

<ol>
	<li>Abrir la aplicaci&oacute;n <strong>NetGuard</strong> y aceptar todas las solicitudes de permisos que nos pida.</li>
	<li>Presionar el bot&oacute;n de Opciones. Est&aacute; en&nbsp;la esquina superior derecha o tambi&eacute;n manteniendo presionado el bot&oacute;n capacitivo inferior de la derecha.</li>
	<li>Seleccionar <strong>Ajustes</strong>.</li>
	<li>Seleccionar <strong>Copia de seguridad</strong>.</li>
	<li>Seleccionar <strong>URL de descarga del archivo hosts</strong>.</li>
	<li>Eliminar la URL existente y agregar&nbsp;https://raw.githubusercontent.com/Gonzalox/hosts-elementt/master/hosts</li>
	<li><em>(Opcional, puedes pasar al paso 8)</em> Si quieres un bloqueo que,&nbsp;adem&aacute;s de bloquear la publicidad y el malware espec&iacute;fico del Element Flash II, tambi&eacute;n bloquee la mayor&iacute;a de la publicidad en internet puedes usar la siguiente URL en reemplazo de la anterior:&nbsp;https://raw.githubusercontent.com/Gonzalox/hosts-elementt/master/hosts-full</li>
	<li>Verifica que la URL que ingresaste est&aacute; correcta.</li>
	<li>Selecciona <strong>Aceptar</strong>.</li>
	<li>Selecciona <strong>Descargar archivo hosts</strong>.</li>
	<li>Esperar a que se descargue correctamente.</li>
	<li>Volver atr&aacute;s, al men&uacute; de <strong>Ajustes</strong></li>
	<li>Selecciona <strong>Opciones Avanzadas</strong>.</li>
	<li>Verifica que las siguientes opciones esten marcadas/activadas: <strong>Administrar aplicaciones de sistema</strong>, <strong>Filtrar tr&aacute;fico</strong>, <strong>Bloquear nombres de dominio</strong>.</li>
	<li>Volver atr&aacute;s, a la pantalla de inicio de NetGuard.</li>
	<li><strong>Activar el toggle</strong>&nbsp;de funcionamiento de NetGuard&nbsp;en la esquina superior izquierda. Marcar la opci&oacute;n &#39;Conf&iacute;o en esta aplicaci&oacute;n&#39; cuando nos la solicite (y cualquier otra que pudiera aparecer).</li>
	<li>Salir de la aplicaci&oacute;n.</li>
	<li>Desactivar <strong>Wi-Fi</strong> y <strong>datos m&oacute;viles</strong>, lo cual se puede hacer desde el men&uacute; de notificaciones de Android que aparece al&nbsp;deslizar desde arriba hacia abajo.</li>
	<li><strong>Reiniciar el dispositivo</strong> (manteniendo el bot&oacute;n de apagado presionado y seleccionar la opci&oacute;n <strong>Reiniciar</strong>).</li>
	<li>Esperar a que el dispositivo se haya iniciado completamente.</li>
	<li><strong>Abrir la aplicaci&oacute;n de NetGuard</strong> y esperar 15 segundos.</li>
	<li>Activar <strong>Wi-Fi</strong> o <strong>datos m&oacute;viles</strong>.</li>
	<li>YAY! Estamos listoco.</li>
</ol>

<h3>Consideraciones</h3>

<ul>
	<li><u><strong>Esta protecci&oacute;n no es infalible:</strong></u> Pueden quedar popups, banners o avisos aleatorios de parte del sistema. Tratar&eacute; de actualizar la lista cada vez que vaya detectando m&aacute;s solicitudes de conexiones a servidores maliciosos, asi que tambi&eacute;n considera actualizar tu archivo hosts de vez en cuando para estar en la &uacute;ltima version, con solo llevar a cabo el procedimiento del paso <strong>10</strong> es suficiente para estar al d&iacute;a.&nbsp;Recuerda que tambi&eacute;n puedes colaborar con este proceso aqu&iacute; en Github o enviandome un mensaje con la direcci&oacute;n del servidor a bloquear y los pasos para replicar su aparici&oacute;n.</li>
	<li>Al realizar un reinicio o apagado del dispositivo&nbsp;deber&aacute;s repetir los pasos&nbsp;<strong>18, 19, 20 y 21</strong>. Esto porque la activaci&oacute;n de Wi-Fi o datos m&oacute;viles tiene prioridad y se realiza antes de que la aplicaci&oacute;n NetGuard pueda cargarse autom&aacute;ticamente, esta situaci&oacute;n permite que los servidores maliciosos tengan una ventana de acceso suficiente como para descargar la publicidad sin ser filtrados.</li>
	<li>Luego de aplicar este bloqueo, <strong>la aplicaci&oacute;n de Navegador (que trae por defecto el dispositivo) queda totalmente funcional</strong> y sin publicidad. En caso de seguir presentando problemas, entra a las opciones del navegador y elimina todos los datos que puedas (historial, cookies, cach&eacute;, etc), despu&eacute;s restaura&nbsp;de fabrica las opciones del navegador. Cuando hayas realizado eso, ve a las opciones de la aplicaci&oacute;n del navegador v&iacute;a Android y borra los datos/cach&eacute; (En Nova Launcher: Manten presionado el icono del Navegador desde el caj&oacute;n de aplicaciones, arr&aacute;stralo hacia la parte superior del escritorio que aparecer&aacute; &#39;Info de la aplicaci&oacute;n&#39; y ah&iacute; busca la opci&oacute;n de borrar datos/cach&eacute;)</li>
	<li>El gasto de bater&iacute;a puede aumentar debido a los procesos de NetGuard, el cual requiere crear un VPN local que siempre est&aacute; funcionando en segundo plano. Si utilizas la aplicaci&oacute;n exactamente igual a esta gu&iacute;a&nbsp;el&nbsp;gasto no deber&iacute;a ser tan considerable ya que no ocupa el resto de las funciones que involucra un uso m&aacute;s intensivo.</li>
</ul>

<h3>Bugs</h3>

<ul>
	<li>Popup&nbsp;aleatorio&nbsp;(no a pantalla completa) que simula ser de Google Play aparece de vez en cuando a&uacute;n sin tener conexi&oacute;n, se est&aacute; investigando.</li>
	<li>La aplicaci&oacute;n <strong>TBrowser</strong> (maliciosa) ignora los bloqueos HTTPS (443), se est&aacute; investigando.</li>
</ul>

<h3>Cr&eacute;ditos</h3>

<ul>
	<li><a href="https://github.com/StevenBlack/hosts" target="_blank">StevenBlack Hosts</a>, usado en hosts-full para bloquear la publicidad en general y no limitada solo a la de este dispositivo.</li>
	<li><a href="https://github.com/M66B/NetGuard/" target="_blank">M66B&nbsp;NetGuard</a>, aplicaci&oacute;n usada para integrar el archivo hosts y as&iacute; bloquear la publicidad/malware.</li>
</ul>
