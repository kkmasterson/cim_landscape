# Invoice System Component Wireframe

## Quick Actions Bar
┌──────────────────────────────────────────────────────────────┐
│ [+ New Invoice] [+ New Estimate] [Recent] [Templates] [Search]│
└──────────────────────────────────────────────────────────────┘

## Invoice/Estimate Creation
┌──────────────────────────────────────────────────────────────┐
│ New Document [Toggle: Invoice▼|Estimate]    [Save] [Preview] │
├──────────────────────────────────────────────────────────────┤
│ Client: [Select Client ▼]         Date: [Select 📅]         │
│ Property: [Select Property ▼]     Due: [+30 days ▼]         │
├──────────────────────────────────────────────────────────────┤
│ Services & Items                                             │
│ [+ Add Service] [+ Add Item] [Load Template ▼]              │
│ ┌────────────────────────────────────────────────────────┐  │
│ │ Service: [Weekly Maintenance ▼]                        │  │
│ │ └─ Base Rate: [$85.00/visit]                          │  │
│ │    [✓] Mowing ($50)  [✓] Edging ($20)  [✓] Cleanup ($15) │
│ │    Notes: [Standard cut height 3"]                     │  │
│ ├────────────────────────────────────────────────────────┤  │
│ │ Materials:                                             │  │
│ │ [+ Add Material] [Recent Materials ▼]                  │  │
│ │ • Premium Mulch - 3 bags × $8.99                      │  │
│ │ • Grass Seed - 1 bag × $24.99                         │  │
└──────────────────────────────────────────────────────────────┘

## Summary Panel
┌──────────────────────────────────────────────────────────────┐
│ Subtotal: $156.95                                           │
│ Tax (7.5%): $11.77                                          │
│ Total: $168.72                                              │
│                                                             │
│ [Save as Template] [Convert to Invoice] [Send to Client]    │
└──────────────────────────────────────────────────────────────┘

## Document Storage & History
┌──────────────────────────────────────────────────────────────┐
│ Recent Documents                    [Filter ▼] [Search 🔍]   │
├──────────────────────────────────────────────────────────────┤
│ Today                                                        │
│ • INV-2024-123 - John Smith - $168.72 [Paid ✓]             │
│ • EST-2024-445 - Sarah Jones - $250.00 [Pending]           │
├──────────────────────────────────────────────────────────────┤
│ Last Week                                                    │
│ • INV-2024-122 - Mike Johnson - $85.00 [Paid ✓]            │
│ • EST-2024-444 - Tom Brown - $175.00 [Accepted]            │
└──────────────────────────────────────────────────────────────┘

## Key Features:
1. Unified Invoice/Estimate Creation
   - Quick toggle between invoice and estimate
   - Real-time calculations
   - Service package templates
   - Material cost tracking
   - Tax calculation

2. Smart Templates
   - Save common service combinations
   - Pre-filled pricing
   - Customizable packages
   - Seasonal service templates
   - Quick load templates

3. Client Integration
   - Auto-fill client details
   - Property-specific pricing
   - Service history reference
   - Payment integration
   - Client communication

4. Document Management
   - Secure storage
   - Search functionality
   - Status tracking
   - Payment tracking
   - Export options (PDF, Excel)

5. Mobile Support
   - On-site estimate creation
   - Digital signature capture
   - Photo attachment
   - Offline capability
   - Quick invoice generation

## Integration Points:
1. Client Database
   - Contact information
   - Property details
   - Service history
   - Payment preferences

2. Payment Processing
   - Online payments
   - Recurring billing
   - Payment tracking
   - Auto-reminders

3. Service Scheduling
   - Job completion triggers
   - Automatic invoice generation
   - Service verification
   - Time tracking

4. Reporting System
   - Revenue tracking
   - Service analytics
   - Client history
   - Payment analytics

## Mobile Quick Actions
┌─────────────────────────────┐
│ [📸 Photo] [✍️ Signature]  │
│ [💰 Payment] [📤 Send]     │
└─────────────────────────────┘ 