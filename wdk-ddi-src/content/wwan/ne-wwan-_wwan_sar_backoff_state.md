---
UID: NE:wwan._WWAN_SAR_BACKOFF_STATE
title: _WWAN_SAR_BACKOFF_STATE
author: windows-driver-content
description: The WWAN_SAR_BACKOFF_STATE enumeration specifies the state of SAR backoff for a mobile broadband (MBB) modem's antennas.
ms.assetid: 2c4aeedf-4c2c-4efe-8c3f-fe5c6b7d6009
ms.author: windowsdriverdev
ms.date: 08/20/2018
ms.topic: enum
ms.keywords: _WWAN_SAR_BACKOFF_STATE, WWAN_SAR_BACKOFF_STATE, *PWWAN_SAR_BACKOFF_STATE, 
ms.prod: windows-hardware
ms.technology: windows-devices
req.header: wwan.h
req.include-header:
req.target-type:
req.target-min-winverclnt: Windows 10, version 1703
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.ddi-compliance:
req.max-support:
req.typenames: WWAN_SAR_BACKOFF_STATE, *PWWAN_SAR_BACKOFF_STATE
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	wwan.h
api_name: 
-	_WWAN_SAR_BACKOFF_STATE
product:
- Windows
targetos: Windows
---

# _WWAN_SAR_BACKOFF_STATE enumeration

## -description

The **WWAN_SAR_BACKOFF_STATE** enumeration specifies the state of SAR backoff for a mobile broadband (MBB) modem's antennas.

## -enum-fields

### -field WwanSarBackoffStatusDisabled

SAR back off is disabled in the modem.

### -field WwanSarBackoffStatusEnabled 

SAR back off is enabled in the modem.

## -remarks

This enumeration is used in the [**WWAN_SAR_CONFIG_INFO**](ns-wwan-_wwan_sar_config_info.md) structure and the [**WWAN_SET_SAR_CONFIG**](ns-wwan-_wwan_set_sar_config.md) structure.

## -see-also

[MB SAR Platform Support](https://docs.microsoft.com/windows-hardware/drivers/network/mb-sar-platform-support)

[OID_WWAN_SAR_CONFIG](https://docs.microsoft.com/windows-hardware/drivers/network/oid-wwan-sar-config)

[**WWAN_SAR_CONFIG_INFO**](ns-wwan-_wwan_sar_config_info.md)

[**WWAN_SET_SAR_CONFIG**](ns-wwan-_wwan_set_sar_config.md)