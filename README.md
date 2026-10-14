# AI-Powered Legal Document Generator

def generate_document():
    print("=== AI-Powered Legal Document Generator ===")

    name = input("Enter your name: ")
    document_type = input("Enter document type (Agreement/Notice/Contract): ")
    purpose = input("Enter the purpose: ")
    date = input("Enter the date: ")

    document = f"""
    LEGAL DOCUMENT

    Document Type: {document_type}
    Date: {date}

    This document is prepared for {name}.

    Purpose:
    {purpose}

    Terms and Conditions:
    1. Both parties agree to the terms mentioned in this document.
    2. All information provided must be true and accurate.
    3. Any changes to this agreement must be mutually accepted.
    4. The document should comply with applicable laws.

    Name: {name}
    Date: {date}

    Signature: __________________
    """

    print("\nGenerated Legal Document:")
    print(document)


generate_document()
