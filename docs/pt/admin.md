## Descri��o detalhada

O adaptador de administra��o � usado para configurar todas os adaptadores no ioBroker. Ele fornece uma interface web, que pode ser chamado sob o '<endere�o IP do servidor>:8081`. Este adaptador � criado diretamente durante a instala��o do ioBroker.

Pelo GUI do adaptador pode ser usada as seguintes fun��es:

* Instala��o de adaptadores adicionais
* Acesso � vis�o geral dos objetos
* Acesso � vis�o geral dos estados dos objetos
* Acesso � administra��o de usu�rios e grupos
* Acesso ao arquivo de log
* Administra��o dos hosts

## Instala��o

Este adaptador � criado diretamente durante a instala��o do ioBroker. Uma instala��o manual n�o � necess�ria

## Configura��o

![adapter_admin_konfiguration](img/admin_konfiguration.png)

#### IP

Aqui � deve ser inserido o endere�o IP sob o qual o adaptador pode ser alcan�ado. V�rias op��es Ipv4 e Ipv6 est�o dispon�veis.
<span style="color: #ff0000;">**O default � 0.0.0.0\. Isso n�o pode ser alterado!**</span>

#### Porta

Aqui � definida a porta sob a qual o administrador pode ser chamado. Se v�rios servidores da Web estiverem sendo executados no servidor, esta porta deve ser adaptada para que n�o haja problemas com portas duplicadas.

#### Criptografia

Se voc� quiser usar o protocolo seguro https, voc� deve marcar esta caixa.

#### Autentica��o

Se voc� quiser que use uma autentica��o, voc� deve marcar esta caixa.

## Funcionamento

Usando o navegador da Web, v� para a p�gina a seguir:

`<Endere�o IP do servidor>:8081`

## Abas

Na p�gina principal do administrador existem v�rias abas. Na instala��o b�sica, as abas s�o vistas como mostrado. Usando o �cone de l�pis na parte superior direita (1), outras abas podem ser adicionadas ou retiradas.

![iobroker_adapter_admin_001a](img/admin_ioBroker_Adapter_Admin_001a.jpg)

Informa��es detalhadas s�o fornecidas nos links dos t�tulos.

### [Adaptador](admin/tab-adapters.md)

Aqui os adaptadores dispon�veis podem ser instalados e gerenciados.

### [Inst�ncias](admin/tab-instances.md)

Aqui as inst�ncias j� instaladas podem ser configuradas.

### [Objetos](admin/tab-objects.md)



### [Estados](admin/tab-states.md)

Os estados atuais dos objetos.

### [Eventos](admin/tab-events.md)

Uma lista de atualiza��es dos estados.

### [Grupos](admin/tab-groups.md)

Aqui voc� pode criar os grupos de usu�rios e controlar os direitos desse.

### [Usu�rios](admin/tab-users.md)

Aqui voc� pode criar os usu�rios e adicionar eles aos grupos existentes.

### [Enumera��es](admin/tab-enums.md)

Aqui est�o listados os favoritos, as kategorias e os quartos.

### [Hosts](admin/tab-hosts.md)

Informa��es sobre o computador onde ioBroker est� instalado. Voc� pode aqui atualizar a vers�o do js-controler. Se uma nova vers�o estiver dispon�vel, a aba aparece em verde.

### [Log](admin/tab-log.md)


### [Configura��es do sistema](admin/tab-system.md)

![Configura��es do administrador do sistema](img/admin_Systemeinstellungen.jpg)