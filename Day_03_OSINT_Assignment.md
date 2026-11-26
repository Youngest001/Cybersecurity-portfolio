# OSINT REPORT

**Target:** owasp.org  
**Organization:** OWASP  
**Analyst:** Modebelu Ifechukwu Solomon  
**Date:** November 26, 2026

## 1. Executive Summary

This investigation gathered publicly available information about owasp.org using passive OSINT tools. WHOIS, Wayback Machine, crt.sh and username-search tools were used to examine domain information, website history, certificate records and username footprint.

## 2. Introduction

**Objective:** To gather publicly available information about owasp.org.

**Scope:** The investigation used passive OSINT sources, including WHOIS, Wayback Machine, crt.sh and username-search tools.

**Methodology:** WHOIS was used for domain information, Wayback Machine for website history, crt.sh for certificate records, and What's My Name for username searches.

## 3. Findings

### 3.1 Domain Registration
The domain was registered through GoDaddy.com, LLC on September 21, 2001. It expires on September 21, 2031. Its nameservers are fay.ns.cloudflare.com and west.ns.cloudflare.com.

### 3.2 Archive History
A Wayback Machine snapshot from March 2, 2016, was accessed. It showed an OWASP homepage describing its focus on software security.

### 3.3 Subdomains
The crt.sh search showed identities including:

- www.owasp.org
- m.owasp.org
- rustore.owasp.org
- mail.owasp.org
- *.owasp.org

### 3.4 Username Footprint
The username solomankins was searched using What's My Name. Results included Internet Archive and Rumble. The username was also manually verified on X as @solomankins.

## 4. Analysis

The findings may indicate that OWASP has maintained its domain for many years and has multiple domain identities associated with its web infrastructure.

The username search may indicate that solomankins appears on several publicly searchable platforms, although search results alone do not confirm account ownership.

## 5. Conclusion and Recommendations

The investigation gathered publicly available information about OWASP using passive OSINT tools.

**Recommendations:**
1. Regularly monitor domain records and certificates for unexpected changes.
2. Review publicly exposed information to reduce unnecessary exposure.

## 6. Appendices

- **Appendix A:** WHOIS screenshot.
- **Appendix B:** Wayback Machine screenshot.
- **Appendix C:** crt.sh screenshot.
- **Appendix D:** What's My Name screenshot.
