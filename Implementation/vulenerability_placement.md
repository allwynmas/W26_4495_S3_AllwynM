# Vulnerability Placement Strategy

This document outlines where each planned vulnerability will be embedded within the application. The goal is to integrate vulnerabilities into realistic workflows rather than isolated demo pages.

## 1. SQL Injection (Backend)
**Location:** Login form or search functionality  
**Reason:** Demonstrates insecure query construction and improper input handling.

## 2. Cross-Site Scripting (XSS) (Frontend)
**Location:** Comment box, profile bio, or feedback form  
**Reason:** Allows users to see how unescaped input affects rendered HTML.

## 3. Broken Authentication
**Location:** Login session handling  
**Reason:** Demonstrates weak session validation and insecure credential checks.

## 4. Insecure Direct Object Reference (IDOR)
**Location:** Profile page or user-specific resources  
**Reason:** Shows how predictable IDs can expose unauthorized data.

## 5. CSRF
**Location:** Any form that performs a state-changing action  
**Reason:** Demonstrates missing or misconfigured CSRF tokens.

## 6. Insecure File Upload
**Location:** File upload page  
**Reason:** Allows demonstration of insufficient file validation.

## Notes
This placement plan ensures each vulnerability is tied to a real feature, improving the educational value of the platform.
