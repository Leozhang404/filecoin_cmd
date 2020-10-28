# filecoin_cmd
'Summarize common commands'


- 转账 

   lotus send --from wallet_address to_address [FIL_count] 

- 签名及验证

   lotus wallet sign wallet_address origin_code

   lotus wallet verify wallet_address sign_code

- 扇区历史状态变化

   louts-miner sectors status --log SECTOR_ID
