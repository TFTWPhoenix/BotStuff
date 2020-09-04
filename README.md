The issue is with .startsWith:


TypeError: Cannot read property 'startsWith' of undefined
    at Client.bot.on (/media/tftwphoenix/Files/Projects/Starbotv3.1/bot.js:21:36)
    at Client.emit (events.js:198:13)
    at FullPacketParser.deserializer.on (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/minecraft-protocol/src/client.js:89:12)
    at FullPacketParser.emit (events.js:198:13)
    at addChunk (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/readable-stream/lib/_stream_readable.js:298:12)
    at readableAddChunk (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/readable-stream/lib/_stream_readable.js:280:11)
    at FullPacketParser.Readable.push (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/readable-stream/lib/_stream_readable.js:241:10)
    at FullPacketParser.Transform.push (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/readable-stream/lib/_stream_transform.js:139:32)
    at FullPacketParser._transform (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/protodef/src/serializer.js:82:10)
    at FullPacketParser.Transform._read (/media/tftwphoenix/Files/Projects/Starbotv3.1/node_modules/readable-stream/lib/_stream_transform.js:177:10)
