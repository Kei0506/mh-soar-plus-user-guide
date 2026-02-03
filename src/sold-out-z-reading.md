# Sold Out / Z-Reading

Ang **Sold Out / Z-Reading** ay ginagamit para i-record ang **daily sales summary** ng store.

Kasama dito ang:

- **Gross sales** ng araw
- Mga **expenses**
- **Tender amounts** (cash, etc.)
- Pag-upload ng supporting images
- Pag-send ng record para ma-sync sa **iDempiere**
    
👉 Karaniwang ginagawa ito **end of day**.

---

## Step 1: Open Sold Out / Z-Reading

1. Sa menu, piliin ang **Sold Out / Z-Reading**
2. Lalabas ang prompt:
> **“Do you want to create a new sold out record?”**
3. Piliin ang **Yes**

---

## Step 2: Review Header Details

Mapupunta ka sa page na may mga sumusunod:
- **Document Number** (auto-generated)
- **Branch Name**
- **Sales Date**
    
### Pag-edit ng Sales Date (Kung kinakailangan)

- I-tap ang **Edit** kung kailangan baguhin ang date
- Siguraduhing tugma ang **sales date** sa actual business date
  
---

## Step 3: Add Sales Line

1. Piliin ang **Sales Line**
2. Lalabas ulit ang prompt:
> **“Would you like to add an invoice?”**
- **Yes** → para mag-add ng **expenses**
- **No** → diretso na sa **Gross Sales**
    

---

## Step 4: Add Invoices (Expenses)

Kung pinili ang **Yes**:
- I-encode lahat ng **expenses** for the day
- I-check mabuti ang details
- Kapag tapos na, magproceed na

👉 Kung **walang expenses**, pwedeng i-skip ang step na ito.

---

## Step 5: Enter Gross Sales

- I-encode ang **gross sales** ng araw ayon sa mga **produktong naibenta**
- I-check kung tugma ang amounts sa actual sales
- Siguraduhing **kumpleto at tama** ang lahat ng entries
    
---

## Step 6: Save Sold Out Record

1. I-tap ang **Save**
2. I-review ang mga na-encode

> ⚠️ **Important**  
> Ang pag-save ay **hindi pa automatic na nagse-send** sa iDempiere.

---

## Step 7: Open Bank Account Menu

1. Sa menu, piliin ang **Bank Account**
2. Piliin ang **bank account** kung saan ide-deposit ang cash
    
---

## Step 8: Encode Tender Types

- Piliin ang **Tender Type** (example: Cash, GCash)
- I-encode ang **amount** para sa bawat tender type
- Maglagay lang ng amounts kung **may ginamit na tender**

👉 Ulitin ito hanggang ma-encode lahat ng tender types.

> ⚠️ **Important (GCash)**  
> Kapag **GCash** ang tender type, ilagay ang **actual total amount**.  
> Ang system na ang **automatic magko-compute ng commission**, kaya huwag bawasan ang amount.

---

## Step 9: Save Bank Account Details

- I-tap ang **Save** pagkatapos ma-encode ang lahat

---

## Step 10: View Sold Out Report

1. Piliin ang **Sold Out Report**
2. I-review ang summary ng:
    - Sales
    - Expenses
    - Tender amounts
      
---

## Step 11: Attach Images (Optional)

1. Piliin ang **Attach Images**
2. Mag-upload ng supporting images (receipts, reports, etc.)

---

## Step 12: Final Save and Confirmation

1. I-tap ang **Save**
2. Lalabas ang confirmation prompt
3. Piliin ang **Yes**

👉 Ire-redirect ka sa **Sold Out Transactions**.

---

## Step 13: Send Transaction

> ℹ️ **Note (Offline vs Online)**  
> Puwedeng **mag-add at mag-save ng Sold Out record kahit offline**.  
> Pero para **ma-send ang transaction**, **kailangang may internet connection**.

### Paano mag-send ng transaction

1. Sa **Sold Out Transactions**, piliin ang record
2. I-tap ang **Send Transaction**
3. I-tap ang **Send**

📤 Ang record ay ise-send at isi-sync sa **iDempiere** kapag online na.

> ✅ **Important**  
> **Only sent transactions** ang lalabas at mare-record sa system.

---

## Best Practices

- Laging i-double check ang amounts bago mag-save
- Siguraduhin ang **tamang sales date**
- Kumpletuhin ang **Bank Account** at **Tender details**
- Mag-attach ng images kung required
- I-send lang ang transaction pagkatapos ma-review ang **Sold Out Report**
