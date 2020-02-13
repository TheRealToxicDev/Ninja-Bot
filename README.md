<html><head><style>
    @import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
    * {
        font-family: 'Montserrat', sans-serif;
    }
    body{
        background-color: #222222 !important;
    }
    p{
        color: white;
        font-size: 16px;
    }
    .item {
        color: white;
        font-size: 14px;
    }
    #menu {
        background: #191919 !important;
        position: fixed;
    }
    #menu ul li a:not(.btn) {
        color: #fff !important;
        background-color: #191919 !important;
        text-transform: uppercase !important;
        padding: 0.400rem 1rem !important;
    }
    #menu ul li a:not(.btn):hover{
        color: #fa9c1f !important;
        background-color: #191919 !important;
        text-transform: uppercase !important;
        padding: 0.400rem 1rem !important;
        transition: color .5s !important;
    }
    #menu div.menu.container {
        background: #191919 !important;
    }
    #bot-details-page .bot-name {
        color: #fff !important;
    }
    .columns {
        flex-direction: column;
        align-items: center;
        text-align: center;
    }
    .container {
        color: white !important;
        box-shadow: none !important;
        border-top: none !important;
    }
    .status {
        display: none !important;
    }
    #bot-info p {
        justify-content: center !important;
    }
    .is-flex {
        display: flex !important;
    }
    .color-blue {
        display: none !important;
    }
    .column p:nth-child(1) {
        display: none !important;
    }
    #bot-stats {
        display: none !important;
    }
    .serversshards a span {
        background-color: transparent !important;
        color: #fff !important;
        margin: 0 !important;
        padding: 0 !important;
    }
    .btn-orange {
        border-radius: 100em;
        background-color: #FFFFFF;
        color: #222222;
        width: 110px !important;
        margin: 20px 10px 0 10px !important;
        padding: 10px;
    }
    .btn-orange:hover {
        background-color: #E8E8E8;
    }
    .botpagebutton {
        border-radius: 100em !important;
        background-color: #272727 !important;
        padding: 0.400rem 1rem !important;
        color: #fff !important;
        height: auto !important;
        line-height: 1.5 !important;
        font-size: 14px !important;
        border: 1px solid #222222 !important;
    }
    .botpagebutton:hover {
        color: #fff !important;
        background-color: #272727 !important;
        border: 1px solid white !important;
        transition: all .3s ease-in !important;
    }
    #delete {
        border: 1px solid #222222 !important;
    }
    #delete:hover {
        border: 1px solid white !important;
        transition: all .3s ease-in !important;
    }
    #report {
        border: 1px solid #222222 !important;
    }
    #report:hover {
        border: 1px solid white !important;
        transition: all .3s ease-in !important;
    }
    #cdm-zone-01 {
        display: none !important;
    }
    .lib a {
        color: #FFFFFF !important;
        font-size: 12px !important;
    }
    .lib a:hover {
        color: #E8E8E8 !important;
    }
    .container.is-widescreen {
        padding: 10px 0 !important;
        border: 0px !important;
    }
    p.bot-description {
        color: #FFFFFF !important;
        font-size: 20px !important;
    }
    .btn-like {
        background-color: #FFFFFF !important;
        color: #222222 !important;
        border-radius: 10px !important;
        border: none !important;
    }
    .btn-like:hover {
        background-color: #E8E8E8 !important;
        color: #222222 !important;
    }
    .atag,
    .bot-tags-title {
        display: none !important;
    }
    #bot-details-page > article > div.container.is-widescreen > div.columns.is-tablet.is-desktop > div.column {
        display: none !important;
    }
    .owners a{
        color: #fff !important;
    }
    #createdby i {
        font-style: normal !important;
    }
    #createdby b {
        background-color: #272727 !important;
        color: #fff;
    }
    b {
        color: white;
    }
    .longdescription {
        background: transparent !important;
    }
    .content {
        background: transparent !important;
        box-shadow: none !important;
    }
    .no:hover:hover {
        background: #222222 !important;
    }
    th.title {
        font-size: 16pt;
        color: white !important;
    }
    th.sub-title {
        font-size: 12pt;
        color: white !important;
    }
    td{
        color: white !important;
    }
    html{
        background: #222222 !important;
    }
    .content h1 {
        color: white !important;
        text-align: center !important;
        font-size: 40px !important;
        font-weight: bold !importantde;
    }
    .content h2 {
        color: white !important;
        text-align: center !important;
        font-size: 50px !important;
        font-weight: bolder !important;
        margin-bottom: -30px !important;
    }
    .content h3 {
        color: white !important;
        text-align: center !important;
        font-weight: bold !important;
        font-size: 30px !important;
        line-height: 35px !important;
        max-width: 1220px !important;
    }
    hr {
        background: white !important;
        border: 3px solid white !important;
    }
    tr {
        background: #3C3C3C !important;
        border: 2px solid white !important;
    }
    tr:hover {
        background-color: #222222 !important;
    }
    .JoinServer {
        border-radius: 100em;
        background-color: #FFFFFF;
        color: #222222;
        transition: all .4s ease-in-out;
        border: 1px solid #222222 !important;
        font-size: 14pt !important;
        padding: 10px !important;
        font: 600 18px "Karla", sans-serif !important;
        margin-bottom: 20px !important;
    }
    .JoinServer:hover {
        border-radius: 100em;
        background-color: #222222;
        color: #FFFFFF;
        transition: all .4s ease-in-out;
        border: 1px solid #FFFFFF !important;
        font-size: 14pt !important;
        padding: 10px !important;
        font: 600 18px "Karla", sans-serif !important;
        margin-bottom: 20px !important;
    }
    .columns .bot-img {
      height: 96px !important;
      width: 96px !important;
      box-shadow: none !important;
      border-radius: 72px !important;
      padding: 0 !important;
      margin: auto !important;
    }
    .centerr {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        border-radius: 10px;
        box-shadow: 0 0 5px 2px #FFFFFF;
        transition: all .5s ease-in-out;
        margin-bottom: 20px !important;
    }
    .centerr:hover {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 55%;
        border-radius: 10px;
        box-shadow: 0 0 5px 2px #fa6060;
        transition: all .5s;
        margin-bottom: 20px !important;
    }
    .gif-img {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 20%;
        border-radius: 10px;
        box-shadow: 0 0 5px 2px #FFFFFF;
    }
    .gif-img:hover {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 25%;
        border-radius: 10px;
        box-shadow: 0 0 5px 2px #fa6060;
        transition: all .5s ease-in;
    }
    .footer {
        background-color: #222222 !important;
    }
    .my-copyright {
        font-size: 14px !important;
        color: #a2a7ab !important;
    }
    .footer a {
        font-size: 12px !important;
        color: #e8e8e8 !important;
    }
    .footer a:hover {
        color: #a2a7ab !important;
        text-decoration: underline !important;
    }
    ::-moz-selection {
        background: #FFFFFF;
        border-radius: 15px;
    }
    ::selection {
        color: black;
        background: #FFFFFF;
    }
    ::webkit-scrollbar {
        width: 9px;
    }
    ::-webkit-scrollbar-thumb {
        background-color: #FFFFFF;
        border-radius: 8px;  
    }
    ::-webkit-scrollbar-track {
        background-color: #252525;
    }
</style>
</head><body><h3>About Ninja</h3>
<h1>Discords Newest and Most Reliable Moderation Bot With A Punch!!,</h1>
<h1>Ninja has over 100+ Commands to keep you entertained and your Server Safe</h1>
<br>
<br>
<br>
<br>
<h1>Ninja Prefix</h1>
<hr>
<table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Default Prefix</td>
<td style="width: 351.467px; height: 23px;">&nbsp;></td>
<td style="width: 237px; height: 23px;">&nbsp;(Customizable)</td>
</tr>
</tbody>
</table>
<h1>Help Command</h1>
<hr>
<table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
<td style="width: 237px; height: 23px;">&nbsp;Usage</td>
</tr>
 <tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">help</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Get usage information for commands</td>
<td style="width: 237px; height: 20px;">&nbsp;>help</td>
</tr>
</tbody>
</table>
<h1>Ninja Setup Commands</h1>
<hr>
<table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>logs</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays information about how to setup your server logs</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>welcomeleave</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays information about how to setup your servers Welcome and Leave Channels.</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>automod</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays information about my AutoMod features and how to use them.</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>prefix &lt;newPrefix&gt;</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Change your servers Default Prefix for the bot (WILL NOT UPDATE IN HELP COMMANDS)</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>botinfo</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays some information about the bot such as Version and Total Commands</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>issue</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Report an issue with the bot and send it to the developer</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>itunes &lt;songName&gt;</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Searches the specified song on iTunes and returns available information.</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>dm &lt;@User#1234&gt; &lt;message&gt;</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Sends the specified message to the specified user via DMs</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>credits</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays some info about my Developer and Contributors</td>
</tr>
</tbody>
</table>
<h1>Admin Command</h1>
<hr>
<table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
<td style="width: 237px; height: 23px;">&nbsp;Usage</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">settings</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;View and change Settings for your Server (Running the command without params will return a list of available settings)</td>
<td style="width: 237px; height: 20px;">&nbsp;>settings &lt;command&gt;</td>
</tr>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Example Settings commands</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
<td style="width: 237px; height: 23px;">&nbsp;Usage Example</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">antijoin</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Enable/Disable AntiJoin for the Server</td>
<td style="width: 237px; height: 20px;">&nbsp;>antijoin &lt;enable&gt;</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">autorole</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Enable/Disable AutoRole on user join</td>
<td style="width: 237px; height: 20px;">&nbsp;>autorole enable &lt;roleName&gt;</td>
</tr>
</tbody>
</table>
<h1>Economy Commands</h1>
<hr><table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
 
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
<td style="width: 237px; height: 23px;">&nbsp;Usage</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">profile</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Returns the specified users Profile (XP, Level ect) (Defaults to your profile if no params provided)</td>
<td style="width: 337px; height: 20px;">&nbsp;>profile or >profile &lt;@User#1234&gt;</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">deposit</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Deposit money into your bank account.</td>
<td style="width: 337px; height: 20px;">&nbsp;>deposit &lt;amount&gt;</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">withdrawl</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Withdrawl money from your bank account.</td>
<td style="width: 337px; height: 20px;">&nbsp;>withdrawl &lt;amount&gt;</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">work</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Go to work for the day and earn some cash</td>
<td style="width: 337px; height: 20px;">&nbsp;>work</td>
</tr>
</tbody>
</table>
<h1>Fun Commands</h1>
<hr><table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
 
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>yoda &lt;text&gt;</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Will return the provided text in yoday style.</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>tattoo &lt;@User#1234&gt;</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Displays the specified users Avatar as a tattoo</td>
</tr>
</tbody>
</table>
<h1>Work Commands</h1>
<hr><table border="0" cellpadding="10" style="width:100%;border-color:none;margin-left:auto;margin-right:auto;">
 
<tbody>
<tr style="height: 25px; background: #222222 !important;">
<td style="width: 163.533px; height: 28px;">&nbsp;Command</td>
<td style="width: 351.467px; height: 23px;">&nbsp;Description</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>hack</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Hacks a random Business or Server to earn money</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>construction</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Work a day as a Construction worker to earn money</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">>prostitute</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Work a day as a Prostitute to earn money</td>
</tr>
<tr style="height: 20px;">
<td style="width: 163.533px; height: 20px;">&nbsp;<span style="color: white;">developer</span></td>
<td style="width: 351.467px; height: 20px;">&nbsp;Work a day as a Developer for a Random company to earn money</td>
</tr>
</tbody>
</table>
<br>
<br>
<br>
<div class="footer">
    <p class="my-copyright">Copyright © 2019-2020 Toxic Dev | Team Toxic</p>
    <p class="my-copyright">Ninja/Ninja Bot is not affiliated with the Twitch streamer known as "Ninja"</p>
    <p class="my-copyright">The Commands List above will be updated frequently! Please check back often.</p>
    <a target="_blank" onclick="trackCampaignWebClick('', 'description');" rel="nofollow" href="https://discord.gg/NeeaqnC">Join My Support Server Here</a>
</div></body></html>
 
[![Discord](https://discordapp.com/api/guilds/668701870663008257/widget.png?style=banner2)](https://discord.gg/NeeaqnC)
