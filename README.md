# nz-hosts-blocklist
Hosts file blocklist to block ads and trackers in NZ apps. 
Includes: Gaspy NZ petrol price app

## Blocked Domains

| Domain | Purpose |
|--------|---------|
| campaigns.gaspy.nz | Gaspy sponsored fuel price ads (2degrees, Gull etc) |
| graph.facebook.com | Facebook ad/tracking SDK |
| ad-analytics-prodnz.prod.gaspy-integrations.nz | Ad analytics backend |

## Usage

### AdAway (Android)
Add this URL to your hosts sources:
```
https://raw.githubusercontent.com/placeholder
```

## Format
Standard hosts file format compatible with AdAway, Pi-hole, and any hosts-based blocker.

## Discovery Method
Domains identified using PCAPdroid traffic analysis on Android.
