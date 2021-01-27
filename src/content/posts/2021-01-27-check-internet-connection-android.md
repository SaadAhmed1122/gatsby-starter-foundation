---
template: blog-post
title: Check Internet Connection Android
slug: Check Internet Connection Android
date: 2021-01-27 22:43
description: Check Status of Internet Connection Android Java
---


```
 public void checkConnection(){
        ConnectivityManager connectivityManager = (ConnectivityManager)
                this.getSystemService(Context.CONNECTIVITY_SERVICE);
        NetworkInfo wifi = connectivityManager.getNetworkInfo(ConnectivityManager.TYPE_WIFI);
        NetworkInfo mobileNetwork = connectivityManager.getNetworkInfo(ConnectivityManager.TYPE_MOBILE);

        if(wifi.isConnected()){
            no_internet.setVisibility(View.GONE);
        }
        else if (mobileNetwork.isConnected()){
            no_internet.setVisibility(View.GONE);
        }
        else{
            no_internet.setVisibility(View.VISIBLE);

        }

    }
```