# AULA-02-PHP-PW

Instalando o PHP via winget

Abra o PowerShell ou o Prompt de Comando (não precisa ser como administrador, mas pode ajudar) e rode:

powershell
```winget search php```

Isso mostra as versões disponíveis (geralmente do pacote oficial PHP.PHP, com várias versões como 8.3, 8.4 etc). Para instalar uma versão específica:

powershell
```winget install PHP.PHP.8.3```

Ou, se quiser deixar o winget escolher a versão mais recente:

powershell
```winget install PHP.PHP```

Depois de instalado, feche e reabra o terminal e confirme que funcionou:

powershell
```php -v```

1 - Abra Visual Studio Code
2 - Vá guia arquivo > Abrir pasta > Cria pasta como nome AT02PW-meunome
