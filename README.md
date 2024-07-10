# Ошибка ssl при запуске discord бота

```
ClientConnectorCertificateError(aiohttp.client_exceptions.ClientConnectorCertificateError: 
Cannot connect to host discordapp.com:443 
ssl:True [SSLCertVerificationError: (1, '[SSL: CERTIFICATE_VERIFY_FAILED] 
certificate verify failed: certificate has expired (_ssl.c:1108)')]
```

#### 1. Установить сертификат (не помогло)
[https://crt.sh/?id=2835394](https://github.com/Rapptz/discord.py/issues/4159#issuecomment-640107584)

#### 2. Обновить сертификаты (решение)
Запусть от админа script, например, так ![image](https://github.com/foxkodland/ssl_discord/assets/102648390/45315930-3f19-4a6e-8566-a937261104b1)

