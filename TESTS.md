# OCTT Results

## A_Security_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
| TC_A_01_CSMS | Basic Authentication - Valid username/password combination |&#x2611; <sub><sup>PASS<sup></sub>|
| TC_A_02_CSMS | Basic Authentication - Username does not equal ChargingStationId |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_A_03_CSMS | Basic Authentication - Invalid password |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_A_04_CSMS | TLS - server-side certificate - Valid certificate     |&#x2610; <sub><sup>PASSED<sup></sub>|
|TC_A_06_CSMS | TLS - server-side certificate - TLS version too low     |&#x2610; <sub><sup>PASSED<sup></sub>|
|TC_A_09_CSMS | Update Charging Station Password for HTTP Basic Authentication - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_A_10_CSMS | Update Charging Station Password for HTTP Basic Authentication - Rejected |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_A_19_CSMS | Upgrade Charging Station Security Profile - Accepted     |&#x2610; <sub><sup>ISSUE<sup></sub>|

## B_Provisioning_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_B_01_CSMS | Cold Boot Charging Station - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_02_CSMS | Cold Boot Charging Station - Pending |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_06_CSMS | Get Variables - single value |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_07_CSMS | Get Variables - multiple values |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_09_CSMS | Set Variables - single value |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_10_CSMS | Set Variables - multiple values |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_12_CSMS | Get Base Report - ConfigurationInventory |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_13_CSMS | Get Base Report - FullInventory |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_20_CSMS | Reset Charging Station - Without ongoing transaction - OnIdle |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_21_CSMS | Reset Charging Station - With Ongoing Transaction - OnIdle |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_22_CSMS | Reset Charging Station - With Ongoing Transaction - Immediate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_25_CSMS | Reset EVSE - Without ongoing transaction |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_26_CSMS | Reset EVSE - With Ongoing Transaction - OnIdle |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_27_CSMS | Reset EVSE - With Ongoing Transaction - Immediate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_30_CSMS | Cold Boot Charging Station - Pending/Rejected - SecurityError |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_31_CSMS | Cold Boot Charging Station - Pending/Rejected - TriggerMessage |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_42_CSMS | Set new NetworkConnectionProfile - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_B_44_CSMS | Set new NetworkConnectionProfile - Failed |&#x2611; <sub><sup>PASS<sup></sub>|

## C_Authorization_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_C_02_CSMS | Local start transaction - Authorization Invalid/Unknown |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_06_CSMS | Local start transaction - Authorization Blocked |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_07_CSMS | Local start transaction - Authorization Expired |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_08_CSMS | Authorization through authorization cache - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_20_CSMS | Authorization through authorization cache - Invalid |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_37_CSMS | Clear Authorization Data in Authorization Cache - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_38_CSMS | Clear Authorization Data in Authorization Cache - Rejected |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_39_CSMS | Authorization by GroupId - Success |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_47_CSMS | Stop Transaction with a Master Pass - With UI - All transactions |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_48_CSMS | Stop Transaction with a Master Pass - With UI - With UI - Specific transactions |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_C_49_CSMS | Stop Transaction with a Master Pass - Without UI |&#x2611; <sub><sup>PASS<sup></sub>|

## E_Transactions_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_E_01_CSMS | Start transaction options - PowerPathClosed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_02_CSMS | Start transaction options - EnergyTransfer |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_03_CSMS | Local start transaction - Cable plugin first - Success |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_04_CSMS | Local start transaction - Authorization first - Success |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_07_CSMS | Stop transaction options - PowerPathClosed - Local stop |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_08_CSMS | Stop transaction options - EnergyTransfer stopped - StopAuthorized |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_09_CSMS | Start transaction options - EVConnected |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_10_CSMS | Start transaction options - Authorized - Local |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_11_CSMS | Start transaction options - DataSigned |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_12_CSMS | Start transaction options - ParkingBayOccupied |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_14_CSMS | Stop transaction options - EVDisconnected - Charging Station side |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_15_CSMS | Stop transaction options - StopAuthorized - Local |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_16_CSMS | Stop transaction options - Deauthorized - Invalid idToken |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_17_CSMS | Stop transaction options - Deauthorized - EV side disconnect |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_19_CSMS | Stop transaction options - ParkingBayUnoccupied |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_20_CSMS | Stop transaction options - EVDisconnected - EV side (able to charge IEC 61851-1 EV) |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_21_CSMS | Stop transaction options - StopAuthorized - Remote |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_22_CSMS | Stop transaction options - EnergyTransfer stopped - SuspendedEV |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_26_CSMS | Disconnect cable on EV-side - Suspend transaction |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_29_CSMS | Check Transaction status - Transaction with id ongoing - with message in queue |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_30_CSMS | Check Transaction status - Transaction with id ongoing - without message in queue |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_31_CSMS | Check Transaction status - Transaction with id ended - with message in queue |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_33_CSMS | Check Transaction status - Without transactionId - with message in queue |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_34_CSMS | Check Transaction status - Without transactionId - without message in queue |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_38_CSMS | Local start transaction - EV not ready |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_39_CSMS | Stop transaction options - Deauthorized - timeout |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_E_53_CSMS | Reset Sequence Number - CSMS accepting _seqNo_ = 0 at start of transaction |&#x2611; <sub><sup>PASS<sup></sub>|

## F_RemoteControl_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_F_01_CSMS | Remote start transaction - Cable plugin first |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_02_CSMS | Remote start transaction - Remote start first - AuthorizeRemoteStart is true |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_03_CSMS | Remote start transaction - Remote start first - AuthorizeRemoteStart is false |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_04_CSMS | Remote start transaction - Remote start first - Cable plugin timeout |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_06_CSMS | Remote unlock Connector - Without ongoing transaction - Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_11_CSMS | Trigger message - MeterValues - Specific EVSE |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_12_CSMS | Trigger message - MeterValues - All EVSE |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_13_CSMS | Trigger message - TransactionEvent - Specific EVSE |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_14_CSMS | Trigger message - TransactionEvent - All EVSE |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_15_CSMS | Trigger message - LogStatusNotification - Idle |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_18_CSMS | Trigger message - FirmwareStatusNotification - Idle |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_20_CSMS | Trigger message - Heartbeat |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_23_CSMS | Trigger message - StatusNotification - Specific EVSE - Available |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_24_CSMS | Trigger message - StatusNotification - Specific EVSE - Occupied |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_F_27_CSMS | Trigger message - NotImplemented |&#x2611; <sub><sup>PASS<sup></sub>|

## G_Availability_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_G_03_CSMS | Change Availability EVSE - Operative to inoperative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_04_CSMS | Change Availability EVSE - Inoperative to operative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_05_CSMS | Change Availability Charging Station - Operative to inoperative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_06_CSMS | Change Availability Charging Station - Inoperative to operative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_07_CSMS | Change Availability Connector - Operative to inoperative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_08_CSMS | Change Availability Connector - Inoperative to operative |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_11_CSMS | Change Availability EVSE - With ongoing transaction |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_14_CSMS | Change Availability Charging Station - With ongoing transaction |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_17_CSMS | Change Availability Connector - With ongoing transaction |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_G_20_CSMS | Connector status Notification - Lock Failure |&#x2611; <sub><sup>PASS<sup></sub>|

## J_MeterValues_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_J_01_CSMS | Clock-aligned Meter Values - No transaction ongoing |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_02_CSMS | Clock-aligned Meter Values - Transaction ongoing |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_03_CSMS | Clock-aligned Meter Values - EventType Ended |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_04_CSMS | Clock-aligned Meter Values - Signed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_07_CSMS | Sampled Meter Values - EventType Started - EVSE known |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_08_CSMS | Sampled Meter Values - Context Transaction.Begin - EVSE not known |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_09_CSMS | Sampled Meter Values - EventType Updated |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_10_CSMS | Sampled Meter Values - EventType Ended |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_J_11_CSMS | Sampled Meter Values - Signed |&#x2611; <sub><sup>PASS<sup></sub>|

## L_FirmwareManagement_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_L_01_CSMS | Secure Firmware Update - Installation successful |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_02_CSMS | Secure Firmware Update - InstallScheduled |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_03_CSMS | Secure Firmware Update - DownloadScheduled |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_04_CSMS | Secure Firmware Update - RevokedCertificate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_05_CSMS | Secure Firmware Update - InvalidCertificate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_06_CSMS | Secure Firmware Update - InvalidSignature |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_07_CSMS | Secure Firmware Update - DownloadFailed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_08_CSMS | Secure Firmware Update - InstallVerificationFailed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_09_CSMS | Secure Firmware Update - InstallationFailed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_10_CSMS | Secure Firmware Update - AcceptedCanceled |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_11_CSMS | Secure Firmware Update - Unable to cancel |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_L_13_CSMS | Secure Firmware Update - Unable to download/install firmware with ongoing transaction - AllowNewSessionsPendingFirmwareUpdate is false |&#x2611; <sub><sup>PASS<sup></sub>|

## M_ISO_15118_CertificateManagement_CSMS

| Test Case ID | Description | Result |
|--------------|-------------|--------|
|TC_M_01_CSMS | Install CA certificate - CSMSRootCertificate |&#x2611; <sub><sup>PASS<sup>|
|TC_M_02_CSMS | Install CA certificate - ManufacturerRootCertificate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_M_05_CSMS | Install CA certificate - Failed |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_M_13_CSMS | Retrieve certificates from Charging Station - ManufacturerRootCertificate |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_M_18_CSMS | Retrieve certificates from Charging Station - All certificateTypes |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_M_19_CSMS | Retrieve certificates from Charging Station - No matching certificate found |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_M_20_CSMS | Delete a certificate from a Charging Station - Success |&#x2612; <sub><sup>ISSUE<sup></sub>|
|TC_M_21_CSMS | Delete a certificate from a Charging Station - Failed |&#x2612; <sub><sup>ISSUE<sup></sub>|

## N_Diagnostics_CSMS

| Test Case ID   |      Description      |  Result |
|--------------|-------------|--------|
|TC_N_25_CSMS | Retrieve Log Information - Diagnostics Log - Success |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_27_CSMS | Get Customer Information - Accepted + data |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_28_CSMS | Get Customer Information - Accepted + no data |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_29_CSMS | Get Customer Information - Not Accepted |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_30_CSMS | Clear Customer Information - Clear and report + data |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_31_CSMS | Clear Customer Information - Clear and report + no data |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_32_CSMS | Clear Customer Information - Clear and no report |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_34_CSMS | Retrieve Log Information - Rejected |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_35_CSMS | Retrieve Log Information - Security Log - Success |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_36_CSMS | Retrieve Log Information - Second Request |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_N_62_CSMS | Clear Customer Information - Clear and report - customerIdentifier |&#x2611; <sub><sup>PASS<sup></sub>|

## P_DataTransfer_CSMS

| Test Case ID   |      Description      |  Result |
|--------------|-------------|--------|
|TC_P_02_CSMS | Data Transfer to the CSMS - Rejected / Unknown VendorId / Unknown MessageId |&#x2611; <sub><sup>PASS<sup></sub>|
|TC_P_03_CSMS | CustomData - Receive custom data |&#x2611; <sub><sup>PASS<sup></sub>|
