KylinRom CN PhonenumGeoProvider

Thanks for MagicMod to share the code

Usage
-----

    Cursor query = contentResolver.query(Uri.parse("content://com.kylinrom.kmgeoprovider/CN/15110111111"), null, null, null, null);
    query.moveToFirst();
    
    String x = query.getString(0);
    query.close();
