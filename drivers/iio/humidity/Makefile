#
# Makefile for IIO humidity sensor drivers
#

obj-$(CONFIG_DHT11) += dht11.o
obj-$(CONFIG_HDC100X) += hdc100x.o

hts221-y := hts221_core.o \
	    hts221_buffer.o
obj-$(CONFIG_HTS221) += hts221.o
obj-$(CONFIG_HTS221_I2C) += hts221_i2c.o
obj-$(CONFIG_HTS221_SPI) += hts221_spi.o

obj-$(CONFIG_HTU21) += htu21.o
obj-$(CONFIG_SI7005) += si7005.o
obj-$(CONFIG_SI7020) += si7020.o
