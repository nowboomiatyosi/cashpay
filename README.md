# KT For Scheduling Cashpay Payment Workflow

## Backend API Side

### Folder Name
`internal_api`

### Branch Name
`internalapi_scheduling_cashpay`

### Included Files

#### Controller
**File Path:**
`internal-api\config-portal\module\Schedule\src\v2\Controller\SettingController.php`

**Included Functions:**
- `paymentWorkFlowSaveAction`
- `getMasterDataAction`

#### Model
**File Path:**
`internal-api\config-portal\module\Schedule\src\v2\Model\SettingsTable.php`

**Included Functions:**
- `paymentWorkFlowSave`
- `getMasterData`

## Front End Side

### Folder Name
`internal_frontend`

### Branch Name
`internal_scheduling_cashpay`

### Included Files

#### HTML Files
**File Path:**
`internal-front-end\page-cms\pages\payment-scheduling-settings.php`

#### JS Files
**Workflow File:**
`internal-front-end\page-cms\templates\assets\js\payment-scheduling-settings.js`

**Getting Master Data AJAX Calling File:**
`internal-front-end\page-cms\ajax\payment-workflow-items.php`

**Save Payment Workflow AJAX Calling File:**
`internal-front-end\page-cms\ajax\payment-workflow-save.php`

**API Calling Functions File:**
`internal-front-end\page-cms\includes\api-function.php`

## Data Encode/Decode URL

[Data Encode/Decode URL](https://test1internalapi.yosicare.com/portal/registration/v1/test)

## Included Database

**Database Name:**
`yosi_selfschedule`

### Tables
- `payment_qualify_question`
- `payment_locations`
- `payment_provider`
- `payment_appointment_types`
- `payment_workflow`
