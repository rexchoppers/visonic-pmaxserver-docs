# /devices

## Name
/devices

## Description
This method returns a list of devices that are connected to the panel.

## Parameters
This method does not take any parameters.

## Authentication
`User-Token` is required.

`Session-Token` is required.

## Example Request
`GET /devices`

## Example Response
Note: The following devices have had their types, locations and information modified to remove any sensitive information.

```json
[
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "CONTROL_PANEL",
    "zone_type": null,
    "subtype": "VISONIC_PANEL",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "",
    "removable": false,
    "renamable": false
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "POWER_LINK",
    "zone_type": null,
    "subtype": "POWER_LINK",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "",
    "removable": false,
    "renamable": false
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "ZONE",
    "zone_type": "DELAY_2",
    "subtype": "MC303_VANISH",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 8,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      },
      "location": {
        "name": "Front door"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 2,
    "device_type": "ZONE",
    "zone_type": "INTERIOR",
    "subtype": "FLAT_PIR_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 17,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T15:25:11",
          "value": 15
        },
        "temperature": {
          "date": "2025-01-23T11:54:54",
          "value": 11.5
        }
      },
      "location": {
        "name": "Kitchen"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 3,
    "device_type": "ZONE",
    "zone_type": "INTERIOR",
    "subtype": "FLAT_PIR_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 21,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T14:45:57",
          "value": 2
        },
        "temperature": {
          "date": "2025-01-23T10:44:49",
          "value": 15.5
        }
      },
      "location": {
        "name": "Upstairs"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 4,
    "device_type": "ZONE",
    "zone_type": "INTERIOR_FOLLOW",
    "subtype": "FLAT_PIR_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 4,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T08:49:42",
          "value": 2
        },
        "temperature": {
          "date": "2025-01-23T12:51:51",
          "value": 12
        }
      },
      "location": {
        "name": "Living room"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "WL_SIREN",
    "zone_type": null,
    "subtype": "OUTDOOR",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 4,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "PGM",
    "zone_type": "OUTPUT",
    "subtype": "PGM_ON_PANEL",
    "preenroll": false,
    "warnings": null,
    "partitions": [],
    "traits": {
      "location": {
        "name": "Front door"
      },
      "parent": {
        "id": 00000000,
        "port": 1
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "KEYFOB",
    "zone_type": null,
    "subtype": "KEYFOB_ARM_LED",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "owner": {
        "id": 00000000,
        "name": "Joe Bloggs"
      }
    },
    "name": "FOB",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 2,
    "device_type": "KEYFOB",
    "zone_type": null,
    "subtype": "KEYFOB_ARM_LED",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "owner": {
        "id": 00000000,
        "name": "Joe Bloggs"
      }
    },
    "name": "FOB",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "WIRELESS_COMMANDER",
    "zone_type": null,
    "subtype": "LCD_KEYPAD",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 8,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "PROXY_TAG",
    "zone_type": null,
    "subtype": "GENERIC_PROXY_TAG",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "Tag",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 2,
    "device_type": "PROXY_TAG",
    "zone_type": null,
    "subtype": "GENERIC_PROXY_TAG",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "Tag",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 3,
    "device_type": "PROXY_TAG",
    "zone_type": null,
    "subtype": "GENERIC_PROXY_TAG",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "Tag",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 4,
    "device_type": "PROXY_TAG",
    "zone_type": null,
    "subtype": "GENERIC_PROXY_TAG",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "Tag",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 5,
    "device_type": "PROXY_TAG",
    "zone_type": null,
    "subtype": "GENERIC_PROXY_TAG",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {},
    "name": "Tag",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 5,
    "device_type": "ZONE",
    "zone_type": "DELAY_1",
    "subtype": "MC303_VANISH",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 4,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      },
      "location": {
        "name": "Kitchen"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "KITCHEN DOOR",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 6,
    "device_type": "ZONE",
    "zone_type": "DELAY_1",
    "subtype": "MC303_VANISH",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 21,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      },
      "location": {
        "name": "Utility room"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "UTILITY ROOM DOOR",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 7,
    "device_type": "ZONE",
    "zone_type": "PERIMETER",
    "subtype": "FLAT_PIR_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 21,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T15:15:28",
          "value": 2
        },
        "temperature": {
          "date": "2025-01-23T13:21:22",
          "value": 5.5
        }
      },
      "location": {
        "name": "Shed"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 8,
    "device_type": "ZONE",
    "zone_type": "FIRE",
    "subtype": "S_SMOKE_AND_HEAT",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 21,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "temperature": {
          "date": "2025-01-23T08:04:36",
          "value": 12
        }
      },
      "location": {
        "name": "Fire"
      },
      "soak": {
        "enabled": false
      },
      "rarely_used": {
        "enabled": false
      }
    },
    "name": "LOFT SM+H",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 1,
    "device_type": "REPEATER",
    "zone_type": null,
    "subtype": "BASIC_REPEATER",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 17,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 9,
    "device_type": "ZONE",
    "zone_type": "PERIMETER",
    "subtype": "GLASS_BREAK_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 17,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T15:41:06",
          "value": 2
        },
        "temperature": {
          "date": "2025-01-23T14:47:53",
          "value": 11.5
        }
      },
      "location": {
        "name": "Kitchen"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 10,
    "device_type": "ZONE",
    "zone_type": "PERIMETER",
    "subtype": "GLASS_BREAK_SMART",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 21,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      },
      "meteo_info": {
        "brightness": {
          "date": "2025-01-23T15:14:00",
          "value": 2
        },
        "temperature": {
          "date": "2025-01-23T14:47:53",
          "value": 7.5
        }
      },
      "location": {
        "name": "Porch"
      },
      "bypass": {
        "enabled": false
      },
      "soak": {
        "enabled": false
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 2,
    "device_type": "WIRELESS_COMMANDER",
    "zone_type": null,
    "subtype": "LCD_PRG_KEYPAD",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 17,
        "repeater": 1,
        "last_updated": "2025-01-23 13:42:03"
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  },
  {
    "id": 00000000,
    "enrollment_id": "109-0000",
    "device_number": 3,
    "device_type": "WIRELESS_COMMANDER",
    "zone_type": null,
    "subtype": "LCD_PRG_KEYPAD",
    "preenroll": false,
    "warnings": null,
    "partitions": [
      1
    ],
    "traits": {
      "rssi": {
        "average": "strong",
        "current": "strong",
        "channel": 8,
        "repeater": null,
        "last_updated": "2025-01-23 13:42:03"
      }
    },
    "name": "",
    "removable": true,
    "renamable": true
  }
]
```
