---
Description: VDS provides structures that define object properties, notifications, and other entities represented in the VDS object model.
ms.assetid: 6a13f5eb-0fa1-48e2-a112-b2254ca28423
title: VDS Structures
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# VDS Structures

\[Beginning with Windows 8 and Windows Server 2012, the [Virtual Disk Service](virtual-disk-service-portal.md) COM interface is superseded by the [Windows Storage Management API](https://msdn.microsoft.com/library/windows/desktop/hh830613).\]

VDS provides structures that define object properties, notifications, and other entities represented in the [VDS object model](vds-object-model.md).



| Structure                                                                               | Description                                                                                                                                                                                                                                                     |
|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**CHANGE\_ATTRIBUTES\_PARAMETERS**](/windows/desktop/api/Vds/ns-vds-_change_attributes_parameters)                  | Defines the partition parameters of a partition style.                                                                                                                                                                                                          |
| [**CHANGE\_PARTITION\_TYPE\_PARAMETERS**](/windows/desktop/api/Vds/ns-vds-_change_partition_type_parameters)         | Describes parameters to be used when changing a partition's type.                                                                                                                                                                                               |
| [**CREATE\_PARTITION\_PARAMETERS**](/windows/desktop/api/Vds/ns-vds-_create_partition_parameters)                    | Defines the partition parameters of a partition style.                                                                                                                                                                                                          |
| [**VDS\_ASYNC\_OUTPUT**](/windows/desktop/api/Vds/ns-vds-_vds_async_output)                                          | Represents output information for the async object.                                                                                                                                                                                                             |
| [**VDS\_CONTROLLER\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_controller_notification)                    | Specifies the valid object status values of a controller.                                                                                                                                                                                                       |
| [**VDS\_CONTROLLER\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_controller_prop)                                    | Defines the properties of a [controller object](controller-object.md).                                                                                                                                                                                         |
| [**VDS\_CREATE\_VDISK\_PARAMETERS**](/windows/desktop/api/Vds/ns-vds-_vds_create_vdisk_parameters)                   | Contains the parameters to be used when a virtual disk is created.                                                                                                                                                                                              |
| [**VDS\_DISK\_EXTENT**](/windows/desktop/api/Vds/ns-vds-_vds_disk_extent)                                            | Defines the properties of a disk extent.                                                                                                                                                                                                                        |
| [**VDS\_DISK\_FREE\_EXTENT**](/windows/desktop/api/Vds/ns-vds-_vds_disk_free_extent)                                 | Describes a free extent on a disk.                                                                                                                                                                                                                              |
| [**VDS\_DISK\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_disk_notification)                                | Represents disk notification information generated by the underlying provider or by VDS for uninitialized disks.                                                                                                                                                |
| [**VDS\_DISK\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_disk_prop)                                                | Defines the properties of a [disk object](disk-object.md).                                                                                                                                                                                                     |
| [**VDS\_DISK\_PROP2**](/windows/desktop/api/Vds/ns-vds-_vds_disk_prop2)                                              | Defines the properties of a [disk object](disk-object.md). This structure is identical to the [**VDS\_DISK\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_disk_prop) structure, except that it also includes the location path and, if the disk is offline, the reason why it is offline.    |
| [**VDS\_DRIVE\_EXTENT**](/windows/desktop/api/Vds/ns-vds-_vds_drive_extent)                                          | Defines the properties of a drive extent.                                                                                                                                                                                                                       |
| [**VDS\_DRIVE\_LETTER\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_drive_letter_notification)               | Represents drive-letter notification information generated by VDS.                                                                                                                                                                                              |
| [**VDS\_DRIVE\_LETTER\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_drive_letter_prop)                               | Represents properties for the drive letter.                                                                                                                                                                                                                     |
| [**VDS\_DRIVE\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_drive_notification)                              | Contains the details of a drive notification.                                                                                                                                                                                                                   |
| [**VDS\_DRIVE\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_drive_prop)                                              | Defines the properties of a [drive object](drive-object.md).                                                                                                                                                                                                   |
| [**VDS\_DRIVE\_PROP2**](/windows/desktop/api/Vds/ns-vds-_vds_drive_prop2)                                            | Defines the properties of a [drive object](drive-object.md). This structure is identical to the [**VDS\_DRIVE\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_drive_prop) structure, except that it includes the enclosure number, bus type, and spindle speed as members.                    |
| [**VDS\_FILE\_SYSTEM\_FORMAT\_SUPPORT\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_file_system_format_support_prop) | Provides information about file systems that are supported for formatting volumes.                                                                                                                                                                              |
| [**VDS\_FILE\_SYSTEM\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_file_system_notification)                 | Represents file system notification information generated by VDS.                                                                                                                                                                                               |
| [**VDS\_FILE\_SYSTEM\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_file_system_prop)                                 | Represents properties for file systems.                                                                                                                                                                                                                         |
| [**VDS\_FILE\_SYSTEM\_TYPE\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_file_system_type_prop)                      | Represents properties that identify file system types.                                                                                                                                                                                                          |
| [**VDS\_HBAPORT\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_hbaport_prop)                                          | Defines the properties of an [HBA port object](startup-and-service-objects.md).                                                                                                                                                                                |
| [**VDS\_HINTS**](/windows/desktop/api/Vds/ns-vds-_vds_hints)                                                         | Contains the automagic hints for a LUN or LUN plex.                                                                                                                                                                                                             |
| [**VDS\_HINTS2**](/windows/desktop/api/Vds/ns-vds-_vds_hints2)                                                       | Contains the automagic hints for a LUN in a storage pool.                                                                                                                                                                                                       |
| [**VDS\_INPUT\_DISK**](/windows/desktop/api/Vds/ns-vds-_vds_input_disk)                                              | Represents input disk information.                                                                                                                                                                                                                              |
| [**VDS\_INTERCONNECT**](/windows/desktop/api/VdsLun/ns-vdslun-_vds_interconnect)                                           | Contains the address data of a physical interconnect.                                                                                                                                                                                                           |
| [**VDS\_IPADDRESS**](/windows/desktop/api/Vds/ns-vds-_vds_ipaddress)                                                 | Defines an IP address and port.                                                                                                                                                                                                                                 |
| [**VDS\_ISCSI\_INITIATOR\_ADAPTER\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_initiator_adapter_prop)        | Defines the properties of an iSCSI [initiator adapter object](startup-and-service-objects.md).                                                                                                                                                                 |
| [**VDS\_ISCSI\_INITIATOR\_PORTAL\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_initiator_portal_prop)          | Defines the properties of an iSCSI [initiator portal object](startup-and-service-objects.md).                                                                                                                                                                  |
| [**VDS\_ISCSI\_IPSEC\_KEY**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_ipsec_key)                                   | Defines the pre-shared key for an iSCSI portal.                                                                                                                                                                                                                 |
| [**VDS\_ISCSI\_PORTAL\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_portal_prop)                               | Defines the properties of an iSCSI [portal object](portal-object.md).                                                                                                                                                                                          |
| [**VDS\_ISCSI\_PORTALGROUP\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_portalgroup_prop)                     | Defines the properties of an iSCSI [portal group object](portal-group-object.md).                                                                                                                                                                              |
| [**VDS\_ISCSI\_SHARED\_SECRET**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_shared_secret)                           | Defines the CHAP shared secret for an iSCSI initiator or target.                                                                                                                                                                                                |
| [**VDS\_ISCSI\_TARGET\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_iscsi_target_prop)                               | Defines the properties of an iSCSI [target object](target-object.md).                                                                                                                                                                                          |
| [**VDS\_LUN\_INFORMATION**](/windows/desktop/api/VdsLun/ns-vdslun-_vds_lun_information)                                    | Contains information about a LUN or disk.                                                                                                                                                                                                                       |
| [**VDS\_LUN\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_lun_notification)                                  | Contains the details of a LUN notification.                                                                                                                                                                                                                     |
| [**VDS\_LUN\_PLEX\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_lun_plex_prop)                                       | Defines the properties of a [LUN plex object](lun-plex-object.md).                                                                                                                                                                                             |
| [**VDS\_LUN\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_lun_prop)                                                  | Defines the properties of a [LUN object](lun-object.md).                                                                                                                                                                                                       |
| [**VDS\_MOUNT\_POINT\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_mount_point_notification)                 | Represents notification information that was returned by the basic or dynamic software provider because a drive letter or volume GUID path changed.                                                                                                             |
| [**VDS\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_notification)                                           | Contains the VDS notification structures specific to each notification target type (subject).                                                                                                                                                                   |
| [**VDS\_PACK\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_pack_notification)                                | Represents pack notification information generated by the underlying basic or dynamic software provider.                                                                                                                                                        |
| [**VDS\_PACK\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_pack_prop)                                                | Represents properties for the [pack object](pack-object.md).                                                                                                                                                                                                   |
| [**VDS\_PARTITION\_INFO\_GPT**](/windows/desktop/api/Vds/ns-vds-_vds_partition_info_gpt)                             | Represent information for a GUID partition table (GPT) partition.                                                                                                                                                                                               |
| [**VDS\_PARTITION\_INFO\_MBR**](/windows/desktop/api/Vds/ns-vds-_vds_partition_info_mbr)                             | Represents information for a master boot record (MBR) partition.                                                                                                                                                                                                |
| [**VDS\_PARTITION\_INFORMATION\_EX**](/windows/desktop/api/vds/ns-vds-_vds_partition_information_ex)                 | This structure is reserved for system use.                                                                                                                                                                                                                      |
| [**VDS\_PARTITION\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_partition_notification)                      | Represents partition notification information generated by the underlying basic or dynamic software provider.                                                                                                                                                   |
| [**VDS\_PARTITION\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_partition_prop)                                      | Defines the properties of a partition.                                                                                                                                                                                                                          |
| [**VDS\_PATH\_ID**](/windows/desktop/api/Vds/ns-vds-_vds_path_id)                                                    | Defines a unique identification for a path.                                                                                                                                                                                                                     |
| [**VDS\_PATH\_INFO**](/windows/desktop/api/Vds/ns-vds-_vds_path_info)                                                | Defines the information for a path.                                                                                                                                                                                                                             |
| [**VDS\_PATH\_POLICY**](/windows/desktop/api/Vds/ns-vds-_vds_path_policy)                                            | Defines the load balance policy as it applies to a particular path.                                                                                                                                                                                             |
| [**VDS\_POOL\_ATTRIBUTES**](/windows/desktop/api/Vds/ns-vds-_vds_pool_attributes)                                    | Defines the attributes of a [storage pool](storage-pool-object.md).                                                                                                                                                                                            |
| [**VDS\_POOL\_CUSTOM\_ATTRIBUTES**](/windows/desktop/api/Vds/ns-vds-_vds_pool_custom_attributes)                     | Defines a custom attribute of a [storage pool](storage-pool-object.md).                                                                                                                                                                                        |
| [**VDS\_PORT\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_port_notification)                                | Defines the details of controller port events.                                                                                                                                                                                                                  |
| [**VDS\_PORT\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_port_prop)                                                | Contains the properties of a [controller port object](controller-port-object.md).                                                                                                                                                                              |
| [**VDS\_PORTAL\_GROUP\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_portal_group_notification)               | Defines the details of iSCSI portal group events.                                                                                                                                                                                                               |
| [**VDS\_PORTAL\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_portal_notification)                            | Defines the details of iSCSI portal events.                                                                                                                                                                                                                     |
| [**VDS\_PROVIDER\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_provider_prop)                                        | Defines the properties of a [provider object](provider-object.md).                                                                                                                                                                                             |
| [**VDS\_REPARSE\_POINT\_PROP**](/windows/desktop/api/Vds/ns-vds-vds_reparse_point_prop)                             | Defines the reparse-point properties of a [volume object](volume-object.md).                                                                                                                                                                                   |
| [**VDS\_SERVICE\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_service_prop)                                          | Defines the properties of the [service object](startup-and-service-objects.md).                                                                                                                                                                                |
| [**VDS\_STORAGE\_DEVICE\_ID\_DESCRIPTOR**](/windows/desktop/api/VdsLun/ns-vdslun-_vds_storage_device_id_descriptor)        | Provides one or more [**VDS\_STORAGE\_IDENTIFIER**](/windows/desktop/api/VdsLun/ns-vdslun-_vds_storage_identifier) structures for a storage device (typically an instance, as opposed to a class, of device).                                                                                      |
| [**VDS\_STORAGE\_IDENTIFIER**](/windows/desktop/api/VdsLun/ns-vdslun-_vds_storage_identifier)                              | Identifies a storage device using a particular code set and type.                                                                                                                                                                                               |
| [**VDS\_STORAGE\_POOL\_DRIVE\_EXTENT**](/windows/desktop/api/Vds/ns-vds-_vds_storage_pool_drive_extent)              | Defines a drive extent that could be used by a [storage pool](storage-pool-object.md).                                                                                                                                                                         |
| [**VDS\_STORAGE\_POOL\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_storage_pool_prop)                               | Defines the properties of a [storage pool object](storage-pool-object.md).                                                                                                                                                                                     |
| [**VDS\_SUB\_SYSTEM\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_sub_system_notification)                   | Contains the details of a subsystem notification.                                                                                                                                                                                                               |
| [**VDS\_SUB\_SYSTEM\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_sub_system_prop)                                   | Defines the properties of a [subsystem object](subsystem-object.md).                                                                                                                                                                                           |
| [**VDS\_SUB\_SYSTEM\_PROP2**](/windows/desktop/api/Vds/ns-vds-_vds_sub_system_prop2)                                 | Defines the properties of a [subsystem object](subsystem-object.md). This structure is identical to the [**VDS\_SUB\_SYSTEM\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_sub_system_prop) structure, except that it includes the supported RAID types and number of enclosures as members. |
| [**VDS\_TARGET\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_target_notification)                            | Defines the details of iSCSI target events.                                                                                                                                                                                                                     |
| [**VDS\_VDISK\_PROPERTIES**](/windows/desktop/api/Vds/ns-vds-_vds_vdisk_properties)                                  | Defines the properties of a virtual disk.                                                                                                                                                                                                                       |
| [**VDS\_VOLUME\_NOTIFICATION**](/windows/desktop/api/Vds/ns-vds-_vds_volume_notification)                            | Represents volume notification information generated by the underlying basic and dynamic software provider.                                                                                                                                                     |
| [**VDS\_VOLUME\_PLEX\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_volume_plex_prop)                                 | Represents properties for the volume-plex object.                                                                                                                                                                                                               |
| [**VDS\_VOLUME\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_volume_prop)                                            | Defines the properties for a [volume object](volume-object.md).                                                                                                                                                                                                |
| [**VDS\_VOLUME\_PROP2**](/windows/desktop/api/Vds/ns-vds-_vds_volume_prop2)                                          | Defines the properties of a [volume object](volume-object.md). This structure is identical to the [**VDS\_VOLUME\_PROP**](/windows/desktop/api/Vds/ns-vds-_vds_volume_prop) structure, except that it also includes the volume GUIDs.                                                       |
| [**VDS\_WWN**](/windows/desktop/api/Vds/ns-vds-_vds_wwn)                                                             | Defines a world-wide name (WWN).                                                                                                                                                                                                                                |



 

 

 


