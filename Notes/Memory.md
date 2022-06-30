# Memory
Collection of hardware elements in a computer into which we store information

**Byte-Addressable Memory** - each byte has a separate address

CPU -> Memory - during a *write* cycle <br>
Memory -> CPU - during a *read* cycle

**Read Only Memory (ROM)**
- programmed into device, only allows reads during operation
- *Nonvolatile* - contents remain even if power is removed
- Can quickly read from ROM. Not the case for writing
- Much denser than RAM (Can fit more ROM than RAM on a microcontroller)

**Random Access Memory (RAM)**
- stores temporary information, allows read/write during operation
- *Volatile* - lost when power removed

Create the bits that make up a register with flip-flops

| Value | SI Decimal | SI Decimal | ----- | Value | IEC Binary | IEC Binary |
| ----- | ---------- | ---------- | ----- | ----- | ---------- | ---------- |
| 1000<sup>1</sup> | k | kilo- | | 1024<sup>1</sup> | Ki | kibi- |
| 1000<sup>2</sup> | M | mega- | | 1024<sup>2</sup> | Mi | mebi- |
| 1000<sup>3</sup> | G | giga- | | 1024<sup>3</sup> | Gi | gibi- |
| 1000<sup>4</sup> | T | tera- | | 1024<sup>4</sup> | Ti | tebi- |
| 1000<sup>5</sup> | P | peta- | | 1024<sup>5</sup> | Pi | pebi- |
| 1000<sup>6</sup> | E | exa- | | 1024<sup>6</sup> | Ei | exbi- |
| 1000<sup>7</sup> | Z | zetta- | | 1024<sup>7</sup> | Zi | zebi- |
| 1000<sup>8</sup> | Y | yotta- | | 1024<sup>8</sup> | Yi | yobi- |

## Endianness
**Big Endian** - MSB is stored at lower address <br>
**Little Endian** - LSB is stored at lower address

![32-bit Numbers](https://courses.edx.org/assets/courseware/v1/85349ffaffc67ad2cd67faa160b22d2a/asset-v1:UTAustinX+UT.6.10x+3T2019+type@asset+block/32bitendian.png)<figcaption><b>*32 bit Number*</b></figcaption>
<br><br>
![Little Endian](https://courses.edx.org/assets/courseware/v1/9bd8c0dd607e05184175983fa423bc76/asset-v1:UTAustinX+UT.6.10x+3T2019+type@asset+block/littleEndian32.png)<figcaption><b>*Little Endian*</b></figcaption>
<br><br>