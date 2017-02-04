# nodemculuasnippets package

Snippets for NodeMCU Lua script development. This project is under development.

Available modules snippets
* adc
* adxl345
* am2320
* apa102
* bit
* bme280
* bmp085
* cjson
* coap
* cron
* crypto
* dht
* encoder
* enduser setup
* file
* gpio
* hmc5883l
* http
* hx711
* I²C
* l3g4200d
* mDNS (Multicast DNS)
* MQTT
* net
* node (Just a part of it. I will add more later.)

If you want to use function in sub module, You must add : (colon) after a variable then type a prefix.

Like this `(variable):(prefix)`

Example:
`mqttcc:mqttcon[Enter]` becomes `mqttcc:connect(host, port, secure, autoreconnect, established_callback, failure_callback)`
