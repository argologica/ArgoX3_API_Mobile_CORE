Nel core terremo la patch con tutti le funzionalità, ma salveremo nella repo del cliente, sempre versionandole, le patch con ogni versione rilasciatogli:

############################# GESTIONE PATCH PROTOCOL CORE ##############################

- inserire a mano i campi delle Tabelle Standard:AMSKZON, ACTPAR:rispettivamente YVISBLOC YSCANMODE,YSENDAX3M 
- inserire a mano i campi delle Videate Standard:AMK1,AMK2, ACT:rispettivamente YVISBLOC YSCANMODE,YSENDAX3M 
- creare Servizio REST (a mano)
- creare POOL (a mano)







############################# GESTIONE PATCH APP CORE ##############################





############################### GESTIONE  TRATTAMENTI (CORE/APP_CORE) ##############################

- Creare una patch monografica (modalità "standard") solamente dedicata e contenente i trt di Core
- Creare una patch monografica (modalità "standard") solamente dedicata e contenente i trt associata al set di moduli di cui si vuole  fare la patch



################################################### CONTROLLI POST PATCH ##############################################

- Controllare valorizzazione campo YVISBLOC
- Controllare valorizzazione campo YSCANMODE
- Controllare valorizzazione campo YSENDAX3M