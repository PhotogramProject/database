# database
Данните се съхраняват в MySQL база данни, в съответните таблици, които ползват различните
секции, съответно journeys, images, users. Цялата информация за потребителите, се запазват в
таблицата users, а паролите се съхраняват в криптиран вид под формата на хеш за максимална
защита на потребителя. В таблицата journeys се съхраняват всички пътешествия и данните за тях,
като име, коментар, рейтинг и автор. В таблицата images се съхраняват данни за снимките и всички
EXIF данни.
