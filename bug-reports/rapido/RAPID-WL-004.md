# RAPID-WL-004

## Bug Title
Liked location is not getting unliked from the search section

## Application Tested
Rapido Android Application

## Testing Type
Independent Exploratory Testing

## Severity
Medium

## Priority
Medium

## Environment
- Platform: Android
- Source: Public Play Store Build
- Device: Samsung Android Device

## Preconditions
- User is logged into the application
- A location is already marked as liked/saved

## Steps to Reproduce
1. Open the Rapido mobile application
2. Navigate to the search section
3. Tap the Like/Heart icon on a saved location
4. Tap the Like/Heart icon again to unlike the location
5. Observe the behaviour

## Expected Result
The location should be removed from the liked/saved state after tapping the Like/Heart icon again.

## Actual Result
The location continues appearing in the liked state even after tapping the Like/Heart icon again.

## Reproducibility
Always (100%)

## Impact
Users may be unable to properly manage saved locations due to incorrect toggle behaviour.

## Attachment
Screen recording attached (`wishlistRapido.mp4`)
