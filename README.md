# greek-letter-shortcuts
Autohotkey (`.ahk`) file containing shortcuts for Greek letters (e.g. "tau_g" -> "τ").

**Examples:**
- "Gamma_g" -> "Γ"
- "alpha_g" -> "α"
- "vartheta_g" -> "ϑ"

This requires (AutoHotKey)[https://autohotkey.com/] to be installed.

To get this code to run on startup (rather than having to manually run it each time you want to use it), just set the installed `greek letters.ahk` file to run on startup.

Full code is below. Type the text encased in double colons, and AHK will autoreplace it with the corresponding Greek letter. If you click any other keys (e.g. backspace, escape, arrow keys), the code may not recognise the string.

```
#SingleInstance Force ; automatically replaces old instance of script when it is re-run
#Hotstring NoMouse ; so mouse clicks don't reset hotstring recogniser
#Hotstring c o *; ensuring case-sensitivity | omit ending character of auto-replace | end character not required to trigger auto replace

; Uppercase Greek letters
::Alpha_g::Α
::Beta_g::Β
::Gamma_g::Γ
::Delta_g::Δ
::Epsilon_g::Ε
::Zeta_g::Ζ
::Eta_g::Η
::Theta_g::Θ
::Iota_g::Ι
::Kappa_g::Κ
::Lambda_g::Λ
::Mu_g::Μ
::Nu_g::Ν
::Xi_g::Ξ
::Omicron_g::Ο
::Pi_g::Π
::Rho_g::Ρ
::Sigma_g::Σ
::Tau_g::Τ
::Upsilon_g::Υ
::Phi_g::Φ
::Chi_g::Χ
::Psi_g::Ψ
::Omega_g::Ω

; Lowercase Greek letters
::alpha_g::α
::beta_g::β
::gamma_g::γ
::delta_g::δ
::epsilon_g::ε
::zeta_g::ζ
::eta_g::η
::theta_g::θ
::iota_g::ι
::kappa_g::κ
::lambda_g::λ
::mu_g::μ
::nu_g::ν
::xi_g::ξ
::omicron_g::ο
::pi_g::π
::rho_g::ρ
::sigma_g::σ
::tau_g::τ
::upsilon_g::υ
::phi_g::φ
::chi_g::χ
::psi_g::ψ
::omega_g::ω

; Alternative forms
::varsigma_g::ς ; Alternative form of lowercase sigma
::vartheta_g::ϑ ; Alternative form of theta
::varphi_g::ϕ ; Alternative form of phi
::varepsilon_g::ϵ ; Alternative form of epsilon
```
