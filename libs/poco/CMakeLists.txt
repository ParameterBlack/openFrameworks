# Nothing to do here for OSX
set(OF_HEADER_FILES ${OF_HEADER_FILES} include PARENT_SCOPE)
set(OF_CORE_LIBS ${OF_CORE_LIBS}
        lib/osx/PocoCrypto.a
        lib/osx/PocoData.a
        lib/osx/PocoDataSQLite.a
        lib/osx/PocoFoundation.a
        lib/osx/PocoJSON.a
        lib/osx/PocoMongoDB.a
        lib/osx/PocoNet.a
        lib/osx/PocoNetSSL.a
        lib/osx/PocoUtil.a
        lib/osx/PocoXML.a
        lib/osx/PocoZip.a
        PARENT_SCOPE)
