# ✅ Test Cases: CleanCity - Based on User Experience

| TC ID | Feature | Description | Steps to Reproduce | Expected Result | Actual Result | Status |
|-------|---------|-------------|---------------------|------------------|----------------|--------|

| TC-001 | User Registration | Register a new user with valid data | 1. Go to Register page → 2. Fill in name, email, password → 3. Submit | User is redirected to login page with success message | Redirects silently to login page without any message | ❌ Fail |

| TC-002 | Pickup Request | User submits a pickup request | 1. Login → 2. Fill pickup form with future date and required info → 3. Submit | Confirmation message + Request appears in dashboard | Confirmation shows, but request does NOT appear in dashboard | ❌ Fail |

| TC-003 | Blog Comment | Submit a comment on a blog post | 1. Go to blog → 2. Click comment → 3. Type message and post | Comment should display below post | Comment appears after posting,then when refreshed it disappears | ❌ Fail |

| TC-004 | Community Feed | Create a community post | 1. Login → 2. Go to Community → 3. Post a message | Post appears instantly in feed | Works correctly | ✅ Pass |

| TC-005 | Community Feed | Like and comment on a post | 1. Click like/comment on any post | Interaction is saved and displayed | Works correctly | ✅ Pass |

| TC-006 | User Profile | View profile activities (requests/comments) | 1. Go to profile page | Activities like requests and comments are listed | Only edit profile details work; no activity shows | ❌ Fail |

| TC-007 | Admin Login | Admin sees their name and dashboard | 1. Login as admin | Name shows on dashboard + manage requests visible | Admin name displays, but "Manage Requests" has no data | ⚠️ Partial |

| TC-008 | Access Control | Admin restricted from using user-only features | 1. Login as Admin → 2. Try using user pickup form | Restricted or redirected | Admin can use user features like regular users | ❌ Fail |

| TC-009 | Waste Type Validation | Submit form without selecting waste type | 1. Leave waste type empty → Submit | Error message appears | No validation appears | ❌ Fail |

| TC-010 | Pickup Cancellation | Cancel a pending request | 1. Submit request → 2. Go to dashboard → 3. Cancel it | Request status updates to "Cancelled" | Request not visible, cancel not possible | ❌ Fail |

