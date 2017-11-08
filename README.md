# psooproggo
## 3. Encapsulation
### 2 Encapsulation Defined
Encapsulation
- Accessing a service on an object without knowing how that service is implemented.  


### 4 Package-oriented Design
```
package payment
type CreditAccount struct{
  accountNumber string
  accountOwner string
}
func (c CreditAccount) AccountNumber() String
func (c CreditAccount) AccountOwner() string
func (c CreditAccount) AccountCredit() float32
```


## 4. Message Passing
### 2 Message Passing
Message Passing
- Sending a message to an object, but letting that object determine what to do with it

## 5. Composition
### 2 Inheritance and Composition
- Inheritance
behaviour reuse strategy where a type is based upon another's type, allowing it to inherit functionality from the base type
- Composition
behaviour reuse strategy where a type contains objects that have desired functionality. this type delegates calls to those objects to use their behaviors/


## 6. Polymorphism
###
