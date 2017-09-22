# metro-stax-ex
This project contains a few extensions to complement JSR-173 StAX API in the following areas:

* Enable parser instance reuse (which is important in the high-performance environment like JAXB and JAX-WS)
* Improve the support for reading from non-text XML infoset, such as FastInfoset.
* Improve the namespace support.
